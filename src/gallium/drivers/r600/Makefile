TOP = ../../../..
include $(TOP)/configs/current

LIBNAME = r600

LIBRARY_INCLUDES = \
	$(shell pkg-config libdrm --cflags-only-I)

C_SOURCES = \
	r600_asm.c \
	r600_blit.c \
	r600_buffer.c \
	r600_helper.c \
	r600_pipe.c \
	r600_query.c \
	r600_resource.c \
	r600_shader.c \
	r600_state.c \
	r600_texture.c \
	r700_asm.c \
	evergreen_state.c \
	eg_asm.c \
	r600_translate.c \
	r600_state_common.c \
	r600_upload.c

include ../../Makefile.template
