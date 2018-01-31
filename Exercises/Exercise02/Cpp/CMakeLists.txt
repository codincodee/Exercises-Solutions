add_executable(Exercise02 vadd_c.cpp wtime.cpp device_info.cpp)

target_link_libraries(Exercise02 ${OPENCL_LIBRARIES})
