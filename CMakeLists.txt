cmake_minimum_required(VERSION 2.8.3)
project(urdf_tutorial)

find_package(catkin)
catkin_package()

install(DIRECTORY urdf_tutorial/
  DESTINATION ${CATKIN_PACKAGE_SHARE_DESTINATION})
