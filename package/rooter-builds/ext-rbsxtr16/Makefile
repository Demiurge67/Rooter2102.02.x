#Owned by DairyMan@Whirlpool
#
#Copyright GNU act.
include $(TOPDIR)/rules.mk

PKG_NAME:=ext-rbsxtr16
PKG_VERSION:=1.000
PKG_RELEASE:=1

PKG_MAINTAINER:=Created by DM/makefile by Cobia@whirlpool
include $(INCLUDE_DIR)/package.mk

define Package/ext-rbsxtr16
  SECTION:=utils
  CATEGORY:=ROOter
  DEPENDS:=+luci +luci-compat +ext-rooter-basic \
		+luci-app-rootervpn +ext-wireguard \
		+bwmon +464xlat \
		+ca-bundle +ca-certificates +libustream-wolfssl \
		+luci-app-sqm +kmod-sched-cake \
		+ext-command +ext-speedtest \
		+openvpn-easy-rsa +openvpn-openssl \
		+ext-extra \
		+nano +picocom +wget +webconsole
  TITLE:=ROOter support for RBSXTR 16M+ routers
  PKGARCH:=all
endef

define Package/ext-rbsxtr16/description
  Helper scripts to enable ROOter support for RBSXTR 16M+ routers
endef


define Build/Compile
endef

$(eval $(call BuildPackage,ext-rbsxtr16))
