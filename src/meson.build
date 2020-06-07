subdir('glad')

src = [
  'main.cpp'
]

gl_exe = executable(
  'glexe',
  src,
  dependencies: sdl2_dep,
  link_with: [glad],
  include_directories: includes
)