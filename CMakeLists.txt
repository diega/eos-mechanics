cmake_minimum_required(VERSION 3.5)
project(eosmechanics VERSION 1.0 LANGUAGES CXX)
find_package(eosio.cdt)

add_subdirectory(contracts output/)
