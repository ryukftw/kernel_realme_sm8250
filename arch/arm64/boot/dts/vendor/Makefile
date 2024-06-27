# SPDX-License-Identifier: GPL-2.0-only
# Copyright (C) 2018-2020 Oplus. All rights reserved.

vendor := $(srctree)/$(src)

#ifndef OPLUS_BUG_STABILITY
#ifneq "$(wildcard $(vendor)/qcom)" ""
#	subdir-y += qcom
#endif
#else
ifeq ($(strip $(BRAND_SHOW_FLAG)), realme)
#realme SM8250 project
subdir-y += 21623
subdir-y += 21733
else
subdir-y += qcom
endif
#endif
