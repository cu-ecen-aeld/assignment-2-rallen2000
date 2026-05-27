CROSS_COMPILE ?= 
CC	= $(CROSS_COMPILE)gcc

ifneq ($(CROSS_COMPILE),)
	SYSROOT	= /home/rallen8/arm-cross-compiler/arm-gnu-toolchain-13.3.rel1-x86_64-aarch64-none-linux-gnu/bin/aarch64-none-linux-gnu-gcc/aarch64-none-linux-gnu/libc
endif

writer:
	$(CC) -o writer writer.c
	
clean:	
	rm -f *.o writer
