cmake_minimum_required(VERSION 3.0)
project(rtspserver)
# 配置编译选项
set(CMAKE_CXX_FLAGS ${CMAKE_CXX_FLAGS} -g)
# 可执行文件输出路径PROJECT_SOURCE_DIR当前文件根目录
set(EXECUTABLE_OUTPUT_PATH ${PROJECT_SOURCE_DIR}/bin)
# 配置文件搜索路径
include_directories(${PROJECT_SOURCE_DIR}/log)
# 加载子目录
add_subdirectory(src)

