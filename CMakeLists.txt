cmake_minimum_required(VERSION 3.0)
project(chat)


set(CMAKE_CXX_FLAGS ${CMAKE_CXX_FLAGS} -g)


set(EXECUTABLE_OUTPUT_PATH ${PROJECT_SOURCE_DIR}/bin)

include_directories(${PROJECT_SOURCE_DIR}/include)
include_directories(${PROJECT_SOURCE_DIR}/include/src)
include_directories(${PROJECT_SOURCE_DIR}/include/src/db)
include_directories(${PROJECT_SOURCE_DIR}/include/src/model)
include_directories(${PROJECT_SOURCE_DIR}/include/src/redis)


add_subdirectory(src)
