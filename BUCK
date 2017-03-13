include_defs('//BUCKAROO_DEPS')

cxx_library(
  name = 'yaml-cpp',
  header_namespace = '',
  srcs = glob([
    'src/**/*.cpp',
  ]),
  headers = subdir_glob([
    ('src', '**/*.h'),
  ]),
  exported_headers = subdir_glob([
    ('include', 'yaml-cpp/**/*.h'),
  ]),
  compiler_flags = [
    '-std=c++11',
  ],
  visibility = [
    'PUBLIC',
  ],
  deps = BUCKAROO_DEPS,
)

# TODO: Google Test
