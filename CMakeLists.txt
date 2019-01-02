cmake_minimum_required(VERSION 3.12)

list(
  APPEND
  CMAKE_MODULE_PATH
  ${CMAKE_SOURCE_DIR}
)
project(
  RenderMake
  VERSION 0.0.0
  DESCRIPTION "Leverage make for rendering 3D scenes."
  HOMEPAGE_URL "https://github.com/brobeson/render-make"
  LANGUAGES Rib SC
)

#add_scene(test test.rib)
#scene_dependencies(
#  test
#  my_shader
#  my_texture
#)
