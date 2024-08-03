cmake_minimum_required(VERSION 3.12)

project(RapidJSON LANGUAGES CXX)
add_library(rapidjson INTERFACE)
target_include_directories(rapidjson INTERFACE include)
target_compile_features(rapidjson INTERFACE cxx_std_20)
