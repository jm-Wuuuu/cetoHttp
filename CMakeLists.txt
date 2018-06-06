PROJECT(cetoHttp)

SET(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -std=c++11 -Wall -fPIC -pthread")
SET(CMAKE_ARCHIVE_OUTPUT_DIRECTORY ${CMAKE_SOURCE_DIR}/build)

ADD_EXECUTABLE(cetoHttp ./src/backend/cetoHttp.cpp)