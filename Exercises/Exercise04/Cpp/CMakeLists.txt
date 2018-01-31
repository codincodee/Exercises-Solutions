add_executable( Exercise04 vadd.cpp )
target_link_libraries( Exercise04 ${OPENCL_LIBRARIES} )

configure_file(vadd.cl ${CMAKE_CURRENT_BINARY_DIR}/vadd.cl COPYONLY)
