cmake_minimum_required(VERSION 3.7)
project(banana)

set(CMAKE_CXX_STANDARD 11)

set(SOURCE_FILES
        banana/README.md
        docs/README.md
        examples/README.md
        tests/README.md
        LICENSE
        README.md)

add_executable(banana ${SOURCE_FILES})