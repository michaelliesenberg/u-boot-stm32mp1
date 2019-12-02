# SPDX-License-Identifier: GPL-2.0+ OR BSD-3-Clause
#
# Copyright (C) 2018, STMicroelectronics - All Rights Reserved
#

ifdef CONFIG_SPL_BUILD
obj-y += ../../st/stm32mp1/spl.o
else
obj-$(CONFIG_CMD_STBOARD) += ../../st/stm32mp1/cmd_stboard.o
endif

obj-y += ../../st/stm32mp1/board.o board.o
