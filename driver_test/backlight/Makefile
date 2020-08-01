obj-m	:= backlight_drv.o
KERNEL	:= /home/friendly/linux-4.4.90

all:
	make -C $(KERNEL) M=`pwd` modules

clean:
	make -C $(KERNEL) M=`pwd` clean
