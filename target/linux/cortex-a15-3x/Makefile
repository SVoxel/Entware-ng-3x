#
# Copyright (C) 2011-2015 Entware
#
# This is free software, licensed under the GNU General Public License v2.
# See /LICENSE for more information.
#

include $(TOPDIR)/rules.mk

ARCH:=arm
BOARD:=cortex-a15-3x
BOARDNAME:=Entware (Cortex-A15, hard float, kernel-3.4.103)
FEATURES:=usb audio pci
KERNEL_PATCHVER:=3.4.103
CPU_TYPE:=cortex-a15
DEFAULT_PACKAGES := toolchain

include $(INCLUDE_DIR)/target.mk

define Target/Description
	Build Software Repository for ARM NASes, like QNAP and Synology.
endef

$(eval $(call BuildTarget))
