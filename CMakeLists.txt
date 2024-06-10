cmake_minimum_required(VERSION 3.27)
project(octopus-server)

set(CMAKE_CXX_STANDARD 17)
set(CMAKE_CXX_STANDARD_REQUIRED ON)
set(CMAKE_EXPORT_COMPILE_COMMANDS ON)

aux_source_directory(./src DIR_SRCS)
add_executable(octopus-server ${DIR_SRCS})
