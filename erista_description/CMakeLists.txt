cmake_minimum_required(VERSION 2.8.3)
project(erista_description)

find_package(catkin REQUIRED COMPONENTS
  urdf
  xacro
  catkin
)

catkin_package()
