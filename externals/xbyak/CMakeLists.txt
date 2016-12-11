# Imported xbyak version: 44f83e61830fb693c13e2c5a7e61ce1fd5924dd2

set(HEADERS
            xbyak/xbyak.h
            xbyak/xbyak_mnemonic.h
            xbyak/xbyak_util.h
            )

add_library(xbyak INTERFACE)
target_include_directories(xbyak INTERFACE ${CMAKE_CURRENT_SOURCE_DIR}/xbyak)
