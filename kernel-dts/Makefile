old-dtb := $(dtb-y)
dtb-y :=
makefile-path := platform/t210/nx/kernel-dts

dtb-$(CONFIG_ARCH_TEGRA_210_SOC) += tegra210-odin.dtb
dtb-$(CONFIG_ARCH_TEGRA_210_SOC) += tegra210b01-odin.dtb
dtb-$(CONFIG_ARCH_TEGRA_210_SOC) += tegra210b01-vali.dtb
dtb-$(CONFIG_ARCH_TEGRA_210_SOC) += tegra210b01-fric.dtb

ifneq ($(dtb-y),)
dtb-y := $(addprefix $(makefile-path)/,$(dtb-y))
endif

dtb-y += $(old-dtb)
