cmake_minimum_required(VERSION 3.10)

project(Forest)

set(CMAKE_CXX_STANDARD 11)
set(CMAKE_CXX_STANDARD_REQUIRED ON)

find_package(SFML COMPONENTS window graphics REQUIRED)

add_executable(Forest
    Animal.cpp
    Carnivore.cpp
    Cat.cpp
    Cow.cpp
    Creature.cpp
    Fish.cpp
    Flower.cpp
    Forest.cpp
    Herbivore.cpp
    Lion.cpp
    main.cpp
    Mushroom.cpp
    Penguin.cpp
    Plant.cpp
    Sparrow.cpp
    Sundew.cpp
)

target_link_libraries(Forest PRIVATE sfml-window sfml-graphics)
