include $(TOPDIR)/rules.mk

PKG_NAME:=dummythird
PKG_VERSION:=1

include $(INCLUDE_DIR)/package.mk

define Package/dummythird
  SECTION:=base
  CATEGORY:=Network
  TITLE:=Third dummy package
  DEPENDS:=+PACKAGE_dummyfirst:dummysecond
endef

define Package/dummythird/description
  Third dummy package
endef

$(eval $(call BuildPackage,dummythird))
