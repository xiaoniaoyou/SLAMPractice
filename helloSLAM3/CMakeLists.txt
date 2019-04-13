
add_library(hello SHARED  HelloSlam.cpp)
add_executable(useHello main.cpp)
target_link_libraries(useHello hello)

