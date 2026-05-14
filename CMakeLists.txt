# Copyright (C) 2026 Arvk
# 
# This program is free software: you can redistribute it and/or modify
# it under the terms of the GNU General Public License as published by
# the Free Software Foundation, either version 3 of the License, or
# (at your option) any later version.

cmake_minimum_required(VERSION 3.25)
project(arvk VERSION 0.1.0 LANGUAGES CXX)

set(CMAKE_CXX_STANDARD 20)
set(CMAKE_CXX_STANDARD_REQUIRED ON)

set(ARVK_SOURCES
    src/arvk.cpp
)

set(ARVK_HEADERS
    include/arvk.hpp
)

add_library(arvk STATIC ${ARVK_SOURCES} ${ARVK_HEADERS})
add_library(arvk::arvk ALIAS arvk)