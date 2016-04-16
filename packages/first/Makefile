include $(TOPDIR)/rules.mk

PKG_NAME:=dummyfirst
PKG_VERSION:=1

include $(INCLUDE_DIR)/package.mk

define Package/dummyfirst
  SECTION:=base
  CATEGORY:=Network
  TITLE:=First dummy package
endef

define Package/dummyfirst/description
  First dummy package
endef

$(eval $(call BuildPackage,dummyfirst))
