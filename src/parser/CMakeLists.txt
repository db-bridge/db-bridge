add_library(libparser parser.cc)

target_include_directories(libparser PUBLIC ${CMAKE_SOURCE_DIR}/include ${CMAKE_SOURCE_DIR}/include/parser)