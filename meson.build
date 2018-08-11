
project('x264', 'c')

cc = meson.get_compiler('c')
x264_dep = declare_dependency(
  dependencies : [cc.find_library('x264', dirs : meson.current_source_dir() + '/lib')],
  include_directories : include_directories('include'))
