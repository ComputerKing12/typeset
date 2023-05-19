cmake_minimum_required(VERSION 3.25)

project(typeset LANGUAGES CXX)

include_directories(include)

add_executable(typeset
	src/main.cpp
)
