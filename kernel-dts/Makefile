old-dtb := $(dtb-y)
dtb-y :=
makefile-path := platform/t210/abca/kernel-dts

dtb-$(CONFIG_ARCH_TEGRA_21x_SOC) += tegra210-abca-01-00.dtb
dtb-$(CONFIG_ARCH_TEGRA_21x_SOC) += tegra210-abca-02-00.dtb
dtb-$(CONFIG_ARCH_TEGRA_21x_SOC) += tegra210-abca-04-00.dtb
dtb-$(CONFIG_ARCH_TEGRA_21x_SOC) += tegra210-abca-04-02.dtb
dtb-$(CONFIG_ARCH_TEGRA_21x_SOC) += tegra210-abca-05-00.dtb
dtb-$(CONFIG_ARCH_TEGRA_21x_SOC) += tegra210-abca-05-01.dtb
dtb-$(CONFIG_ARCH_TEGRA_21x_SOC) += tegra210-abcb-01-00.dtb
dtb-$(CONFIG_ARCH_TEGRA_21x_SOC) += tegra210-abcb-02-00.dtb

ifneq ($(dtb-y),)
dtb-y := $(addprefix $(makefile-path)/,$(dtb-y))
endif

dtb-y += $(old-dtb)
