cmake_minimum_required (VERSION 3.10)
project(ffrdp)
set(SRC_LIST ffrdp/test.c ffrdp/ffrdp.c)
add_executable(ffrdp ${SRC_LIST})
target_link_libraries(ffrdp -lpthread)