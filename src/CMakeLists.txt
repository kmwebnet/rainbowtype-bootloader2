# This file was automatically generated for projects
# without default 'CMakeLists.txt' file.

FILE(GLOB_RECURSE app_sources ${CMAKE_SOURCE_DIR}/src/*.*)

idf_component_register(SRCS ${app_sources} REQUIRES cryptoauthlib)

target_add_binary_data(${COMPONENT_TARGET} "wifimgr/index.html" TEXT)
target_add_binary_data(${COMPONENT_TARGET} "wifimgr/jquery.gz" TEXT)
target_add_binary_data(${COMPONENT_TARGET} "wifimgr/code.js" TEXT)
target_add_binary_data(${COMPONENT_TARGET} "wifimgr/style.css" TEXT)
target_add_binary_data(${COMPONENT_TARGET} "rootca.crt" TEXT)