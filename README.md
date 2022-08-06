# auto-makefile
Makefile that generates file dependencies automatically, while also addressing
header files.  Designed for use in C++ projects, but should be easy to adapt to
other languages.

Feel free to use, modify, and share as much as you like.

This Makefile assumes the source files are stored in the main working directory,
outputs .o files into obj/, and .d files into the obj/deps/ directory.  This
behaviour can be easily changed, however.
