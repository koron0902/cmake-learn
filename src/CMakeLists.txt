add_subdirectory(cmake_sample)

add_executable(${PROJECT_NAME} main.cpp)
target_link_libraries(${PROJECT_NAME} cmake_sample-lib)
