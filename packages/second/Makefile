include $(TOPDIR)/rules.mk

PKG_NAME:=dummysecond
PKG_VERSION:=1

include $(INCLUDE_DIR)/package.mk

define Package/dummysecond
  SECTION:=base
  CATEGORY:=Network
  TITLE:=Second dummy package
  DEPENDS:=+dummyfirst
endef

define Package/dummysecond/description
  Second dummy package
endef

$(eval $(call BuildPackage,dummysecond))
