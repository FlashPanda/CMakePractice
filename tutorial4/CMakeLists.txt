# 最低版本
cmake_minimum_required (VERSION 2.8)

# 设置项目名
project (tutorial4)

# 查找指定目录下的所有源文件，将它保存到变量中
aux_source_directory (./src SRC_DIR)

# 添加可执行文件
add_executable (tutorial4 ${SRC_DIR})