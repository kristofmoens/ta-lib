# CMakeLists files in this project can
# refer to the root source directory of the project as ${HELLO_SOURCE_DIR} and
# to the root binary directory of the project as ${HELLO_BINARY_DIR}.
cmake_minimum_required (VERSION 2.6)
project (talib)

add_subdirectory (ta_abstract)
add_subdirectory (ta_common)
add_subdirectory (ta_func)

add_library(ta_lib STATIC $<TARGET_OBJECTS:ta_abstract> $<TARGET_OBJECTS:ta_common>  $<TARGET_OBJECTS:ta_func>)