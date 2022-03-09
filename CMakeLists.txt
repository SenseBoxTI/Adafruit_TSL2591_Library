cmake_minimum_required(VERSION 3.5)

idf_component_register(SRCS "Adafruit_TSL2591.cpp"
                       INCLUDE_DIRS "."
                       REQUIRES arduino adafruit_sensor)

project(adafruit_tsl2591)
