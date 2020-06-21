subdir('glad')
subdir('stbi')

src = [
  'main.cpp',
  'shader.cpp'
]

gl_exe = executable(
  'glexe',
  src,
  dependencies: sdl2_dep,
  link_with: [glad, stbi],
  include_directories: includes
)