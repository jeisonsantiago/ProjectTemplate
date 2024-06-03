project(core VERSION 0.0.1)

#get all cpp files
set(SRC_FILES
    src/Core.h
    src/Core.cpp
)

add_library(${PROJECT_NAME} ${SRC_FILES})

include_directories(${CMAKE_SOURCE_DIR}/core/src)

