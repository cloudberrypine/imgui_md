
add_library(imgui_md imgui_md.cpp md4c.c)
target_include_directories(imgui_md PRIVATE ../hello_imgui/external/imgui ..)