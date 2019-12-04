aux_source_directory(. SRC_LIST)
set(CMAKE_CXX_STANDARD 17)
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -fconcepts")
add_executable (helloDemo ${SRC_LIST})

