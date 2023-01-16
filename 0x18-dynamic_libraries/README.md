# 0x18. C - Dynamic libraries

In this project, we learn what dynamic library is, how it works, how to create one and how it works. We also get to understand the differences between static and shared libraries.

## Table of contents

libdynamic.so is a C dynamic library containing the function definitions
main.h is the Header files containing the function prototypes
1-create_dynamic_lib.sh is a Bash script that creates a dynamic library called liball.so from all the .c files that are in the current directory
100-operations.so is a C dynamic library that contains C functions that can be called from Python
random.so is aC dynamic library to inject in a giga million program
101-make_me_win.sh is a Bash script to inject the libmask.so library, using LD_PRELOAD, in the giga million program
