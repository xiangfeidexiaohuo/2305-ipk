# Copyright (C) 2016 Openwrt.org
#
# This is free software, licensed under the Apache License, Version 2.0 .
#

include $(TOPDIR)/rules.mk

PKG_NAME:=luci-app-airplay2
PKG_VERSION:=1.0.0
PKG_RELEASE:=1

LUCI_TITLE:=Luci for Apple Airplay2 Receiver
LUCI_DEPENDS:=+alsa-utils +airplay2-openssl
LUCI_PKGARCH:=all

PKG_MAINTAINER:=sbwml <admin@cooluc.com>

include $(TOPDIR)/feeds/luci/luci.mk

# call BuildPackage - OpenWrt buildroot signature
