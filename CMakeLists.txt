cmake_minimum_required(VERSION 3.10.2)
project(make_project)

include_directories(include)

set(SOURCES src/pendu.c
            src/main.c)

add_executable(main
                ${SOURCES}) 
