cxx_library(
  name = 'eastl',
  header_namespace = 'EASTL',
  exported_headers = subdir_glob([
    ('include/EASTL', '**/*.h'),
  ]),
  srcs = glob([
    'source/**/*.cpp',
  ]),
  licenses = [
    'LICENSE',
  ],
  visibility = [
    'PUBLIC',
  ],
  deps = [
    '//test/packages/EABase:eabase',
  ],
)
