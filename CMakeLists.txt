cmake_minimum_required(VERSION 1.6)
project(ProjectProposals)

# Set CMAKE_MODULE_PATH so we can find additional CMake modules.
set(CMAKE_MODULE_PATH ${PROJECT_SOURCE_DIR}/cmake)

# Make sure we can use UseLATEX module for multiple documents.
cmake_policy( SET CMP0002 OLD )
include(UseLATEX)

# Add latex subdirectory
add_subdirectory(latex)
