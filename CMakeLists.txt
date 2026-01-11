cmake_minimum_required(VERSION 4.1)
project(rpg_project)

set(CMAKE_CXX_STANDARD 11)

add_executable(rpg_project main.cpp
        Player.cpp
        Player.h
        Warrior.h
        Priest.h
        Mage.h)
