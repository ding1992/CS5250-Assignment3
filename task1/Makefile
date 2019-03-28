obj-m += hello_world.o

all:
	make -C /lib/modules/$(shell uname -r)/build M=/home/dingguorui/assignment3 modules

clean:
	make -C /lib/modules/$(shell uname -r)/build M=/home/dingguorui/assignment3 clean
