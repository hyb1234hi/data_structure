# 包含公共库
include_directories(${CMAKE_SOURCE_DIR}/Status)

# 生成可执行文件，并链接公共库
add_executable(02.12 SqList.h SqList.c 02.12.c)
target_link_libraries(02.12 Scanf_lib)
