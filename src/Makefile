include $(TOPDIR)/rules.mk

PKG_NAME:=glinet-uboot-scr
PKG_RELEASE:=1


define Build/InstallDev
	$(INSTALL_DIR) $(1)/usr/include/glinet-uboot-scr
	$(CP) $(PKG_BUILD_DIR)/src/*.scr \
		$(1)/usr/include/glinet-uboot-scr/ \

	$(CP) $(PKG_BUILD_DIR)/src/*.scr \
		$(1)/tmp/glinet-uboot.scr
endef

$(eval $(call BuildPackage,glinet-uboot-scr))