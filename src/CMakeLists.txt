cmake_minimum_required (VERSION 3.5)

project(subprojects)

# Add sub directories
add_subdirectory(external/hashmap)
add_subdirectory(common)
add_subdirectory(set_parser)
add_subdirectory(main)