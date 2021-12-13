## opengnb-openwrt

A OpenSource P2P Virtual Network by @gnbdev

### Complie for Openwrt

	# Example install opengnb-openwrt to openwrt/package
	cd openwrt
	git clone https://github.com/gnbdev/opengnb-openwrt package/network/utils/opengnb
	
	# Select Network -> opengnb
	make menuconfig
	make package/opengnb/compile V=99
	
	# Renew download
	rm -f dl/opengnb-*

### Wiki / Bugs Report

Please visit offical page [OpenGNB](https://github.com/gnbdev/opengnb).

### License

GPLv3