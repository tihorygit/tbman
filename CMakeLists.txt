cmake_minimum_required(VERSION 3.8)

project(TBMan)

SET(SOURCE_FILES btree.c eval.c tbman.cpp)

add_library(TBMan STATIC ${SOURCE_FILES})