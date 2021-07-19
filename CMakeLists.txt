cmake_minimum_required(VERSION 3.10.0)

project(refterm VERSION 2 LANGUAGES C CXX)

add_executable(refterm
    refterm.c
    refterm_example_dwrite.cpp

    # refterm_example_d3d11.c
    # refterm_example_dwrite.cpp
    # refterm_example_glyph_generator.c
    # refterm_example_source_buffer.c
    # refterm_example_terminal.c
    # refterm_glyph_cache.c
    # refterm.c
)
target_compile_options(refterm PRIVATE -maes)
