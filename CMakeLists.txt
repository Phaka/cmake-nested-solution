cmake_minimum_required(VERSION 3.16)
project(root C)
 
set( CMAKE_RUNTIME_OUTPUT_DIRECTORY ${CMAKE_SOURCE_DIR}/bin )
set( CMAKE_LIBRARY_OUTPUT_DIRECTORY ${CMAKE_SOURCE_DIR}/lib )

add_subdirectory(project1)
add_subdirectory(project2)
add_subdirectory(project3)
