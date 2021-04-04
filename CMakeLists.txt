cmake_minimum_required(VERSION 3.17)
project(BPF_Cpp_experiments C)

set(CMAKE_C_STANDARD 11)

add_executable(BPF_Cpp_experiments bpf_load.c)
