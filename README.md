# OCMA

OCMA solves very large matrices using disk-based out-of-core technology and Intel Math Kernel Library (Intel MKL), and it adopts the technology of memory-mapped file I/O.

Installation
After downloading, the users will see two files: ocma-0.1.zip is for Windows system ocma-0.1.tar.gz is for Linux/Unix system.
After decompression, one will see two folders: src and bin. The folder src contains all the source code, and the folder bin contains the compiled binary executable. Under the folder bin, two small matrices, SM10 and M3_4 for testing purpose are also provided. 
The program is written in the C language, and it uses Intel Math Kernel Library. So, in order to compile the source code, one needs to install C compiler, e.g., The Intel C/C++ Compilers, The GNU C Compiler or Visual Studio C Compiler will work. Additionally, one needs to install Intel MKL.
When C compiler and MKL are available in the system, one can enter the src folder and modify the makefile based on the C compiler and the MKL paths; then type make or nmake to compile. After that, the ocma executable will be generated in the bin folder. 



