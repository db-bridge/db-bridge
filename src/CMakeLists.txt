add_subdirectory(parser)

add_executable(db-bridge-server main.cc)

target_include_directories(db-bridge-server PUBLIC ${CMAKE_SOURCE_DIR}/include/)