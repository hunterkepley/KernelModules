obj-m += startstop.o
startstop-objs := start.o stop.o
KVER = $(shell uname -r)
DIRN = $(shell pwd)
default:
	make -C /lib/modules/$(KVER)/build M=$(DIRN) modules

clean:
	make -C /lib/modules/$(KVER)/build M=$(DIRN) clean
