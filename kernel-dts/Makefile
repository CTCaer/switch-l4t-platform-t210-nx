old-dtb := $(dtb-y)
dtb-y :=
makefile-path := platform/t210/nx/kernel-dts

dtb-$(CONFIG_ARCH_TEGRA_210_SOC) += tegra210-odin.dtb

ifneq ($(dtb-y),)
dtb-y := $(addprefix $(makefile-path)/,$(dtb-y))
endif

dtb-y += $(old-dtb)
