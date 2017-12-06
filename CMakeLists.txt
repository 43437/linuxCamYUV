cmake_minimum_required(VERSION 2.6)
project(captureoneframe)


include_directories("/home/acmax/app/ffmpeg-dev/include/")

link_directories("/home/acmax/app/ffmpeg-dev/lib/")

add_executable(captureoneframe main.cpp)

target_link_libraries(captureoneframe "avformat" "avcodec" "avutil" "swresample" "swscale" "avdevice")
