add_library(Mamals INTERFACE)
target_include_directories(Mamals INTERFACE ${CMAKE_CURRENT_SOURCE_DIR}/..)
add_subdirectory(Canidae)
add_subdirectory(Felinae)
