cmake_minimum_required(VERSION 3.1)
project (starfield)
set (32BLIT_PATH "~/32blit-beta" CACHE PATH "Path to 32blit.cmake")
include (${32BLIT_PATH}/32blit.cmake)
blit_executable (starfield starfield.cpp)
blit_metadata (starfield metadata.yml)
