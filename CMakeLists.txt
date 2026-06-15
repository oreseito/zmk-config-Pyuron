zephyr_library()
zephyr_include_directories(${APPLICATION_SOURCE_DIR}/include)
zephyr_library_sources(src/board.c src/mini_trackpad_init_reg.c src/mini_trackpad_iqs7211e_init.h)
