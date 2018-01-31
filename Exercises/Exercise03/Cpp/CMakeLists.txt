add_executable( Exercise03 vadd.cpp )
target_link_libraries( Exercise03 ${OPENCL_LIBRARIES} )

configure_file(vadd.cl ${CMAKE_CURRENT_BINARY_DIR}/vadd.cl COPYONLY)
