cmake_minimum_required(VERSION 2.8)
project( eeep_parse )
add_executable( eeep_parse eeep_parse.c )
add_executable( eeep_fruinfo eeep_fruinfo.c )
include_directories(include)
