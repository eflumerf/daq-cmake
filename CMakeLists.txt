cmake_minimum_required(VERSION 3.12)
project(daq-cmake VERSION 1.4.2)

set(CMAKE_MODULE_PATH ${CMAKE_CURRENT_SOURCE_DIR}/cmake ${CMAKE_MODULE_PATH})
include(DAQ)

daq_setup_environment()
daq_install()
