file(GLOB_RECURSE SOURCES ./*.cpp)
add_library(cmake_sample-lib ${SOURCES})

target_include_directories(cmake_sample-lib PUBLIC ${PROJECT_SOURCE_DIR}/src)
set_target_properties(cmake_sample-lib PROPERTIES OUTPUT_NAME cmake_sample)
