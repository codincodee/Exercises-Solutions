cmake_minimum_required(VERSION 2.6)
project(Exercies_Solutions)

# set(CMAKE_MODULE_PATH "${CMAKE_SOURCE_DIR}/cmake")

find_package(OpenCL REQUIRED)

if(CC_CUSTOMIZED)
  add_definitions(-DCC_CUSTOMIZED)
endif()

include_directories(${OPENCL_INCLUDE_DIRS})

include_directories(Exercises)
subdirs(Exercises)
