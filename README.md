Makefile modularizes compiling.

Directories:  
src: .c  
include: .h  
build: .o  

From command line, type make to compile  
Type make clean to clear old build  


### Unity Makefile
This makefile expects you to have a different directory structure and the unity src and header files.

src  
include  
test  
unity  
unity/src  
unity/include  

### Outside sources
1. https://makefiletutorial.com/
   * ...
3. https://devhints.io/makefile
   * ...
5. https://www.throwtheswitch.org/build/make
   * makefile for unity test framework
7. https://gcc.gnu.org/onlinedocs/gcc/Option-Summary.html
   * gcc flags
8. https://www.reddit.com/r/C_Programming/comments/1jd6rm6/c_unity_testing_can_i_just_combine_all_source/
   * unit testing functions that depend on another function
