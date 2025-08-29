cmake_minimum_required(VERSION 3.10)
set(VAR yes)

if(VAR)
    message("VAR is set to true")
else()
    message("VAR is not set or is empty")
endif()