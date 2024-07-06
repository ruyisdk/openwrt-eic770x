# SPDX-License-Identifier: GPL-2.0-only
#
# Copyright (C) 2024 Han Gao <gaohan@iscas.ac.cn>
#

include $(TOPDIR)/rules.mk

ARCH:=riscv64
BOARD:=eswin
BOARDNAME:=Eswin RISC-V boards
FEATURES:=ext4
KERNELNAME:=Image dtbs
SUBTARGETS:=win2030

KERNEL_PATCHVER:=6.6

include $(INCLUDE_DIR)/target.mk

define Target/Description
	Build firmware images for the Eswin RISC-V boards
endef

$(eval $(call BuildTarget))