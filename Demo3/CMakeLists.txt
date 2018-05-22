# CMake 最低版本要要求
cmake_minimum_required (VERSION 2.8)

# 项目信息
project (Demo3)

# 查找当前目录下的所有源文件
# 并将其名称保存到DIR_SRCS 变量
aux_source_directory (. DIR_SRCS)

# 添加math子目录
add_subdirectory (math)

# 包含所有源码文件生成指定目标
add_executable (Demo3 main.cpp)

# 添加链接库
target_link_libraries (Demo3 MathFunctions)
