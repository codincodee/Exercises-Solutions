add_executable( Exercise05 vadd.cpp )
target_link_libraries( Exercise05 ${OPENCL_LIBRARIES} )

configure_file(vadd.cl ${CMAKE_CURRENT_BINARY_DIR}/vadd.cl COPYONLY)
