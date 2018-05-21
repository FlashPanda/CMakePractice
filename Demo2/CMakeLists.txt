# CMake 最低版本要要求
cmake_minimum_required (VERSION 2.8)

# 项目信息
project (Demo2)

# 包含所有源码文件生成指定目标
add_executable (Demo2 main.cpp MathFunctions.cpp)