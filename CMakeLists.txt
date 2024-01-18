cmake_minimum_required(VERSION 3.15)

project(libresec VERSION 1.0 DESCRIPTION "An open source reimplementation of SE server.")

file(GLOB_RECURSE source_list "src/*.c" "src/*.h")
add_executable(${PROJECT_NAME} ${source_list})

