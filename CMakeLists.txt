cmake_minimum_required (VERSION 2.8)
cmake_policy (SET CMP0015 OLD)

set (CMAKE_BUILD_TYPE "" CACHE STRING "")

project (VIVIDCHALK)
set (VIVIDCHALK_VERSION_MAJOR 1)
set (VIVIDCHALK_VERSION_MINOR 0)

set (VIVIDCHALK_INSTALL_DIR
    "${CMAKE_INSTALL_PREFIX}/share/vim/vim73/colors/")

# Copy files with 644 permissions
install(FILES colors/vividchalk.vim
    DESTINATION ${VIVIDCHALK_INSTALL_DIR})

