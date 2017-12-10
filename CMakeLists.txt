cmake_minimum_required(VERSION 2.6)
project(linuxCamYUV)


include_directories("/home/acmax/app/ffmpeg-dev/include/")

link_directories("/home/acmax/app/ffmpeg-dev/lib/")

add_executable(linuxCamYUV main.cpp)

target_link_libraries(linuxCamYUV "avformat" "avcodec" "avutil" "swresample" "swscale" "avdevice")
