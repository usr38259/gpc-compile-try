# GPC compilation try
GPC compilation try in MinGW using GCC 4.8.1  
`patch gcc-3.4.3/gcc/genmodes.c genmodes.patch`  
`gcc-3.4.3/configure --enable-languages=pascal i386-mingw32`  
`make`
