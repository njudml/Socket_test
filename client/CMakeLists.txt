cmake_minimum_required(VERSION 3.13)
project(client)
include_directories(..)

aux_source_directory(. SRC)
add_executable(${PROJECT_NAME} ${SRC})
