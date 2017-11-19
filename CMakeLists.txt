cmake_minimum_required(VERSION 3.0)

project( triangle )

add_executable( triangle
	triangle.cpp )

install(TARGETS triangle DESTINATION bin)
