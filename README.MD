# 32 bit compile
arm-linux-gnueabi-as 001.asm -o 001.o
arm-linux-gnueabi-gcc 001.o -o 001.elf -nostdlib

# 64 bit compile 
aarch64-linux-gnu-as 002.asm -o 002.o
aarch64-linux-gnu-gcc -static 002.o -o 002.elf -nostdlib