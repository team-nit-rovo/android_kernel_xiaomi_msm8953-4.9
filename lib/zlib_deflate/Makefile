#
# This is a modified version of zlib, which does all memory
# allocation ahead of time.
#
# This is the compression code, see zlib_inflate for the
# decompression code.
#
ccflags-y := -O3

obj-$(CONFIG_ZLIB_DEFLATE) += zlib_deflate.o

zlib_deflate-objs := deflate.o deftree.o deflate_syms.o
