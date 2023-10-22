add_executable(server server.cpp)
target_include_directories(server PUBLIC {PROJECT_SOURCE_DIR}/include)
target_link_libraries(server PUBLIC utils)