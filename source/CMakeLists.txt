add_executable(hello main.cpp add.cpp)
target_include_directories(hello PUBLIC ${CMAKE_SOURCE_DIR}/include)
