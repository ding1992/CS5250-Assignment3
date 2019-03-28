obj-m += one_byte_driver.o

all:
	make -C /lib/modules/$(shell uname -r)/build M=/home/dingguorui/assignment3/task2 modules

clean:
	make -C /lib/modules/$(shell uname -r)/build M=/home/dingguorui/assignment3/task2 clean
