qos-y := qos_drv.o qos_core.o
obj-m := qos.o

QOS_MODULE =
all:
	make -C $(KERNELDIR) M=$(shell pwd) modules

clean:
	make -C $(KERNELDIR) M=$(shell pwd) clean



