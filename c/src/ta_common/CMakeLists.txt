
include_directories ("${PROJECT_SOURCE_DIR}/../include")

add_library (ta_common OBJECT ta_global.c 
	ta_retcode.c 
	ta_version.c 
    )
    
# Make sure the compiler can find include files for our Hello library
# when other libraries or executables link to Hello
#target_include_directories (Hello PUBLIC ${CMAKE_CURRENT_SOURCE_DIR})