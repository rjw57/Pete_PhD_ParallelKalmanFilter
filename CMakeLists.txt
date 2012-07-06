# Project specification
project(parallel_kalman)
cmake_minimum_required(VERSION 2.8)

# Module locations
set(CMAKE_MODULE_PATH ${CMAKE_MODULE_PATH} "${CMAKE_CURRENT_SOURCE_DIR}/cmake/Modules/")

# LaTeX support
include(UseLATEX)

add_latex_document(
    ParallelKalmanFilter.tex
    #    IMAGE_DIRS figs
    DEFAULT_PDF
)
