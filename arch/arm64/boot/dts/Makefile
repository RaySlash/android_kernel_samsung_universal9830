# SPDX-License-Identifier: GPL-2.0
dtbo-y += y2s/exynos990-y2s_eur_open_18.dtbo
dtbo-y += y2s/exynos990-y2s_eur_open_05.dtbo
dtbo-y += y2s/exynos990-y2s_eur_open_19.dtbo
dtbo-y += y2s/exynos990-y2s_eur_open_04.dtbo
dtbo-y += y2s/exynos990-y2s_eur_open_17.dtbo
dtbo-y += y2s/exynos990-y2s_eur_open_16.dtbo
dtbo-y += y2s/exynos990-y2s_eur_open_21.dtbo
dtbo-y += y2s/exynos990-y2s_eur_open_06.dtbo
dtbo-y += exynos9830/exynos9830-universal9830_r06.dtbo
dtbo-y += exynos9830/exynos9830-universal9830_r04.dtbo
dtbo-y += exynos9830/exynos9830-smdk9830_r02.dtbo
dtb-y += exynos9830/exynos9830.dtb
dtbo-y += exynos9830/exynos9830-universal9830_r10.dtbo
dtbo-y += exynos9830/exynos9830-universal9830_r05.dtbo

targets += dtbs
DTB_LIST  := $(dtb-y) $(dtbo-y)
always    := $(DTB_LIST)

dtbs: $(addprefix $(obj)/, $(DTB_LIST))

clean-files := *.dtb*
