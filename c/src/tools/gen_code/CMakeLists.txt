
include_directories ("${PROJECT_SOURCE_DIR}/../include")
include_directories ("${PROJECT_SOURCE_DIR}/tools/gen_code")
include_directories ("${PROJECT_SOURCE_DIR}/ta_common")

add_executable (gen_code gen_code.c)
target_link_libraries(gen_code ta_lib)