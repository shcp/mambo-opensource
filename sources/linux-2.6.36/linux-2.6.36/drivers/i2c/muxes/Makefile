#
# Makefile for multiplexer I2C chip drivers.

obj-$(CONFIG_I2C_MUX_PCA954x)	+= pca954x.o

ifeq ($(CONFIG_I2C_DEBUG_BUS),y)
EXTRA_CFLAGS += -DDEBUG
endif
