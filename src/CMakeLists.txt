add_library(Snake_Lib STATIC
						 GameLoop.h
						 GameLoop.cpp)

add_executable(Snake main.cpp)

target_link_libraries(Snake PUBLIC Snake_Lib)