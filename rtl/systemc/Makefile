TARGET_ARCH = linux

CC     = g++
OPT    = -O3 -mcpu=pentiumpro
DEBUG  = -g
OTHER  = -Wall -Wno-deprecated
EXTRA_CFLAGS = $(OPT) $(OTHER)
# EXTRA_CFLAGS = $(DEBUG) $(OTHER)

MODULE = usb
SRCS = usb_ocp_test.cpp usb_ocp.cpp usb_core.cpp usb_fifo512x8.cpp usb_fifo128x8.cpp usb_fifo64x8.cpp usb_ram512x8.cpp usb_ram128x8.cpp usb_ram64x8.cpp usb_phy.cpp usb_tx_phy.cpp usb_rx_phy.cpp usb_sie.cpp usb_pa_sie.cpp usb_pd_sie.cpp usb_pe_sie.cpp usb_dma.cpp usb_fifo2.cpp usb_ep0.cpp usb_crc5.cpp usb_crc16.cpp
OBJS = $(SRCS:.cpp=.o)

include Makefile.defs

