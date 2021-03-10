add_executable(file_io_basis file_io_basis.c)

include_directories(${CMAKE_SOURCE_DIR}/include)

target_link_libraries(file_io_basis PRIVATE utils)