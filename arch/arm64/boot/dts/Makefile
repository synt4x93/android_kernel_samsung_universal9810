# SPDX-License-Identifier: GPL-2.0
dtb-$(CONFIG_DTS_9810_CROWN) += exynos/exynos9810-crownlte_eur_open_26.dtb
dtb-$(CONFIG_DTS_9810_STAR2) += exynos/exynos9810-star2lte_eur_open_26.dtb
dtb-$(CONFIG_DTS_9810_STAR) += exynos/exynos9810-starlte_eur_open_26.dtb

targets += dtbs
DTB_LIST  := $(dtb-y) $(dtbo-y)
always    := $(DTB_LIST)

dtbs: $(addprefix $(obj)/, $(DTB_LIST))

clean-files := *.dtb*
