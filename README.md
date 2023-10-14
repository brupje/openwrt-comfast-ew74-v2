# openwrt-comfast-ew74-v2
Support for comfast ew74 v2

This repository adds support for the Comfast EW74 v2 to OpenWRT 23.05. Due to the small ROM size of 8MB I had to drop SSH server and some other packages from the firmware image.

To upload:
1. Hold reset and power the the device
2. Wait until the wifi LED is no longer blinking
3. Browse to 192.168.1.1
4. Upload the sysupgrade.bin image
