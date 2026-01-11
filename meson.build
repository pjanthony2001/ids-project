project(
  'ids-project',
  'cpp',
  version : '0.1',
  meson_version : '>= 1.3.0',
  default_options : ['warning_level=3', 'cpp_std=c++20'],
)

chesslib_inc = include_directories('include/chess-library/include')

dependencies = [
]

sources = [
  'ids_project.cpp',
]

exe = executable(
  'ids-project',
  sources,
  install : true,
  dependencies : dependencies,
  include_directories : chesslib_inc,
  )

test('basic', exe)
