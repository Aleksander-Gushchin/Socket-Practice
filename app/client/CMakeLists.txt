add_executable(client client.cpp)
target_include_directories(client PUBLIC {PROJECT_SOURCE_DIR}/include)
target_link_libraries(client PUBLIC utils)