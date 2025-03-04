cmake_minimum_required(VERSION 3.15 FATAL_ERROR)
project(mc_sync LANGUAGES CXX)
make_directory(build)
add_executable(mc_sync_server_lib src/main.cpp)