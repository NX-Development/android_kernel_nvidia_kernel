subdir-ccflags-y += -Werror
obj-y += fuse/

obj-y += common.o
obj-y += flowctrl.o
obj-y += pmc.o
obj-y += pmc-r2p.o
obj-y += cvb.o
obj-$(CONFIG_TEGRA_BPMP_MAILMAN) += tegra-bpmp-mailman.o

obj-$(CONFIG_ARM64)	             += pmc-smc-arm64.o
