cmake_minimum_required(VERSION 3.16)
project(HelloWorld)

set(CMAKE_CXX_STANDARD 17)
enable_language(OBJCXX)

add_executable(HelloWorld hello.mm main.cpp)

target_link_libraries(HelloWorld
    "-framework Foundation"
)
