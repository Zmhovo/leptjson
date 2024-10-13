cmake_minimum_required(VERSION 3.22.1)

project(leptjson)

# 指定源文件目录
aux_source_directory(src SRC_LIST)

# 添加头文件目录
include_directories(include)

# 创建可执行文件
add_executable(leptjson ${SRC_LIST})

