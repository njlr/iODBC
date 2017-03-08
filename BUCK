include_defs('//BUCKAROO_DEPS')

cxx_library(
  name = 'iodbc', 
  header_namespace = '',
  exported_headers = subdir_glob([
    ('include', '**/*.h'),
  ]),
  headers = subdir_glob([
    ('iodbc', '**/*.h'),
    ('iodbc', '**/*.ci'),
    ('iodbcinst', '**/*.h'),
    ('iodbcadm', 'iodbcadm.h'),
  ]),
  srcs = glob([
    'iodbc/**/*.c',
    'iodbcinst/**/*.c',
  ]),
  visibility = [
    'PUBLIC',
  ],
  deps = BUCKAROO_DEPS,
)
