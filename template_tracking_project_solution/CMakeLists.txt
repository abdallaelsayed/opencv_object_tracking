cmake_minimum_required(VERSION 2.8)
project( templateTrack )
find_package( OpenCV REQUIRED )
add_executable( templateTrack template_track.cpp )
target_link_libraries( templateTrack ${OpenCV_LIBS} )
