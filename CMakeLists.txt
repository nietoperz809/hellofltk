cmake_minimum_required(VERSION 3.0.0)

project (flk_tester)

INCLUDE_DIRECTORIES(/usr/x86_64-w64-mingw32/sys-root/mingw/include/FL)
LINK_DIRECTORIES(/usr/x86_64-w64-mingw32/sys-root/mingw/lib/)

add_executable(flk_tester WIN32 main.cpp)
TARGET_LINK_LIBRARIES(flk_tester fltk)

