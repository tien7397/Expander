cmake_minimum_required(VERSION 3.22.1)
project(service)
message(">>>>>>>>>>>>>>> service")

add_subdirectory(base64)
add_subdirectory(common)
add_subdirectory(datetime)
add_subdirectory(gpio)
add_subdirectory(json)
add_subdirectory(timer)