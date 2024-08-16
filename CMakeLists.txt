CMAKE_MINIMUM_REQUIRED(VERSION 2.6)

set(CMAKE_CXX_FLAGS "-Wall -Wextra")

# build src
if(BUILD_SRC)
add_subdirectory(src)
endif()

# build test
if(BUILD_TEST)
add_subdirectory(test)
endif()

# build test
if(RUN_TEST)
endif()