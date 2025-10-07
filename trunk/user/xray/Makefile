all:

clean:

romfs:
ifeq ($(CONFIG_FIRMWARE_INCLUDE_XRAY),y)
	$(ROMFSINST) -p -x ./cacert.pem /usr/lib/cacert.pem
	tar -xzf ./xray-linux-mipsle.tar.gz -C $(INSTALLDIR)/usr/sbin/
endif
