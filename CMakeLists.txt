cmake_minimum_required(VERSION 3.12)
set(PICO_BOARD pico_w)

include(pico_sdk_import.cmake)

project(Defcon31-Addon)

pico_sdk_init()

add_subdirectory(src)
add_subdirectory(freertos)