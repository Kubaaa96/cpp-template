include(${CMAKE_SOURCE_DIR}/cmake/Helpers.cmake)

package_add_test(example SOURCES ExampleTest.cpp ${CMAKE_SOURCE_DIR}/src/Example.cpp)