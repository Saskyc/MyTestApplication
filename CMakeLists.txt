cmake_minimum_required(VERSION 4.1)
project(MyTestApplication)

set(CMAKE_CXX_STANDARD 20)

cmake_minimum_required(VERSION 3.16)
project(MyQtApp)

set(CMAKE_CXX_STANDARD 17)

# Create executable
add_executable(MyTestApplication main.cpp)

# Link Qt to your app
target_link_libraries(MyTestApplication Qt6::Widgets)
