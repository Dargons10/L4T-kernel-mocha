GCOV_PROFILE := y

subdir-ccflags-y := -Werror

ifeq ($(CONFIG_ARM64),y)
ccflags-y += -Iarch/arm/mach-tegra/include
endif

ccflags-y += -Iarch/arm/mach-tegra

obj-y += nvmap.o
obj-y += nvmap_init.o
obj-y += nvmap_dev.o
obj-y += nvmap_handle.o
obj-y += nvmap_heap.o
obj-y += nvmap_ioctl.o
obj-y += nvmap_dmabuf.o
obj-y += nvmap_mm.o

obj-$(CONFIG_NVMAP_PAGE_POOLS) += nvmap_pp.o
