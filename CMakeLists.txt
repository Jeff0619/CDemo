# 指定运行此配置文件所需的 CMake 的最低版本；
cmake_minimum_required(VERSION 3.0)
project(cj_demo)     #指定解决方案的名称
set(OUTPUT_DIR ${PROJECT_BINARY_DIR}/x64)     #设置输出目录
add_subdirectory(cj_demo)      
add_subdirectory(cj_xml)	 
