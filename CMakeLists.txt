cmake_minimum_required(VERSION 3.2)

include(cmake/HunterGate.cmake)

HunterGate(
    URL "https://github.com/ruslo/hunter/archive/v0.23.58.tar.gz"
    SHA1 "ee80dc91f91f5eb6892f80a0a92c83b4de8e980a"
)

add_library(
		base64
		base64.c
		base64.h
)
