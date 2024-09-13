cmake_minimum_required(VERSION 3.29)
project(DraftProjectVSCode C)

set(CMAKE_C_STANDARD 11)

include_directories(.)

add_executable(DraftProjectVSCode
    main.c
    main.h
    utilities.c
    utilities.h)
