gcc -c -fPIC *.c #compile the source files into position-independent code (PIC)
gcc -shared -o libyourlibrary.so *.o   # Create the dynamic library
