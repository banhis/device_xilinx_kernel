#
# Makefile for the linux kernel.
#

# Common support
obj-y 				:= common.o timer.o slcr.o scu_gtimer.o board_ep107.o board_zc702.o board_zc770.o board_zc770_xm010.o board_zc770_xm013.o board_zed.o pl330.o platform_devices.o

obj-$(CONFIG_SMP)		+= platsmp.o localtimer.o
obj-$(CONFIG_CPU_IDLE) 		+= cpuidle.o

# Testing
obj-$(CONFIG_XILINX_TEST)	+= test/pl330_test.o
