
project('jpeg', 'c')

cc = meson.get_compiler('c')
install_data(['bin/jpeg62.dll', 'bin/turbojpeg.dll'], install_dir: '/bin')
jpeg_dep = declare_dependency(
  # dependencies : [cc.find_library('jpeg', dirs : meson.current_source_dir()), cc.find_library('legacy_stdio_definitions')],
  dependencies : [cc.find_library('jpeg', dirs : meson.current_source_dir())],
  include_directories : include_directories('include'))
