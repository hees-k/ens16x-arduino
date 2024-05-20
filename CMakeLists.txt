cmake_minimum_required(VERSION 3.5)
idf_component_register(SRCS "src/ens16x.cpp"
                    INCLUDE_DIRS "src/."
                    REQUIRES "arduino" # Library requires Arduino
                    )

project(ens16x-arduino)