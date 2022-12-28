# CMakeList.txt : Top-level CMake project file, do global configuration
# and include sub-projects here.
#
cmake_minimum_required (VERSION 3.8)

project ("accelerated-cpp-solutions")

# Add source to this project's executable.
add_executable (exercise-0-0 src/exercise-0-0.cpp)
add_executable (exercise-0-2 src/exercise-0-2.cpp)
add_executable (exercise-0-4 src/exercise-0-4.cpp)
add_executable (exercise-1-3 src/exercise-1-3.cpp)
add_executable (exercise-1-4 src/exercise-1-4.cpp)
add_executable (exercise-1-5 src/exercise-1-5.cpp)
add_executable (exercise-1-6 src/exercise-1-6.cpp)

if (CMAKE_VERSION VERSION_GREATER 3.12)
  set_property(TARGET exercise-0-0 PROPERTY CXX_STANDARD 20)
  set_property(TARGET exercise-0-2 PROPERTY CXX_STANDARD 20)
  set_property(TARGET exercise-0-4 PROPERTY CXX_STANDARD 20)
  set_property(TARGET exercise-1-3 PROPERTY CXX_STANDARD 20)
  set_property(TARGET exercise-1-4 PROPERTY CXX_STANDARD 20)
  set_property(TARGET exercise-1-5 PROPERTY CXX_STANDARD 20)
  set_property(TARGET exercise-1-6 PROPERTY CXX_STANDARD 20)
endif()