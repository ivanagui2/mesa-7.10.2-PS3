
TOP = ../../../../..
include $(TOP)/configs/current

LIBNAME = radeonwinsys

C_SOURCES = \
	radeon_drm_buffer.c \
	radeon_drm_common.c \
	radeon_r300.c

LIBRARY_INCLUDES = -I$(TOP)/src/gallium/drivers/r300 \
		   $(shell pkg-config libdrm --cflags-only-I)

include ../../../Makefile.template

symlinks:
