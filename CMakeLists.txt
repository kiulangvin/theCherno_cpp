cmake_minimum_required(VERSION 3.12)

project(CPP_APP)

set(CMAKE_CXX_STANDARD 17)


# 搜索所有的cpp,加入到srcs变量中
# aux_source_directory(. SRCS)

# 本工程主程序输出名称
# add_executable(glStudy ${SRCS})
add_executable(cpp_app "main.cpp")


# 将lib连接入softRender
target_link_libraries(cpp_app)
