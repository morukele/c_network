cmake_minimum_required(VERSION 3.5)

project(owe)

file(GLOB SOURCES src/*.c)

set(AUTHOR "Oghenemarho ORUKELE")
set(LICENSE "MIT license")

# Executable
add_executable(owe ${SOURCES})