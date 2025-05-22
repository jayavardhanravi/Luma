cmake_minimum_required(VERSION 3.10)

# Project Name and Version
project(MyCppProject VERSION 1.0)

# Set C++ standard
set(CMAKE_CXX_STANDARD 17)
set(CMAKE_CXX_STANDARD_REQUIRED True)

# Add an executable
add_executable(MyCppProject src/main.cpp)

# Include directories (if you have a separate include folder)
target_include_directories(MyCppProject PUBLIC ${CMAKE_CURRENT_SOURCE_DIR}/include)

# Add options for warnings (optional, but good practice)
if(CMAKE_COMPILER_IS_GNUCC OR CMAKE_COMPILER_IS_CLANG)
  add_compile_options(-Wall -Wextra -Wpedantic)
endif()

# Example of adding a library (if you create one later)
# add_library(MyLibrary src/my_library_source.cpp)
# target_link_libraries(MyCppProject PRIVATE MyLibrary)

# Enable testing with CTest (optional)
enable_testing()

# Example of adding a test
# add_test(NAME MyTest COMMAND MyCppProject) # Assuming your executable can be run as a test or you have a separate test executable
