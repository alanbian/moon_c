obj-m := foo.o foo2.o foo3.o drv3.o drv4.o

#KDIR := 4.14.37-g744dfee
#KDIR := /lib/modules/$(shell uname -r)/build
KDIR := /lib/modules/4.14.37-g744dfee/build
#KDIR := /home/jake/workspace/lsk-4.14

all:
	make -C ${KDIR} M=$(PWD) modules

clean:
	make -C ${KDIR} M=$(PWD) clean
