add_library(stb STATIC impl.cpp stb_image.h)
target_include_directories(stb PUBLIC ./)
