# CMakeFiles.txt inside "SparkFun_u-blox_GNSS" folder
cmake_minimum_required(VERSION 3.5)
idf_component_register(SRCS "src/ESP32_WS2812_Lib.cpp"
                    INCLUDE_DIRS "src/."
                    REQUIRES "arduino-esp32" # Library requires Arduino
                    )

project(ESP32_WS2812_Lib)