cmake_minimum_required(VERSION 2.8.3)
project(bwi_lab_concert)

find_package(catkin REQUIRED)
catkin_package()

install(DIRECTORY concert
  DESTINATION ${CATKIN_PACKAGE_SHARE_DESTINATION})
