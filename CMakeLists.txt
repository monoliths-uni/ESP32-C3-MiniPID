set(CMAKE_CXX_STANDARD_REQUIRED ON)
set(CMAKE_CXX_STANDARD 14)

idf_component_register(SRCS "./src/mini_pid.cpp" INCLUDE_DIRS "./inc")
