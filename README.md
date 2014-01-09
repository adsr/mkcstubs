mkcstubs
========

I use this tool to generate function stubs and synchronize function signatures
across header and source files. It works by scanning header files for function
prototypes, and then ensuring that these functions exist and are up-to-date in
a corresponding source file. It will also re-order functions so they exist in
the same order as in the header file.

The script makes a ton of assumptions about project structure and coding
style, so it's likely not useful for anyone but me.
