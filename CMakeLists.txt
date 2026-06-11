cmake_minimum_required(VERSION 3.16)

include($ENV{IDF_PATH}/tools/cmake/project.cmake)
project(esp32_8048s043)



# HIER EINFÜGEN: Zwingt den Linker, eine Argumenten-Datei zu nutzen
set(CMAKE_NINJA_FORCE_RESPONSE_FILE 1 CACHE INTERNAL "Force response file")
