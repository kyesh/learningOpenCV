cmake_minimum_required(VERSION 2.8)
project( MatDemo )
find_package( OpenCV REQUIRED )
add_executable( MatDemo mat_the_basic_image_container.cpp )
target_link_libraries( MatDemo ${OpenCV_LIBS} )
