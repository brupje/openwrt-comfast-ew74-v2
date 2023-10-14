# openwrt-comfast-ew74-v2
Support for comfast ew74 v2

This repository adds support for the Comfast EW74 v2 to OpenWRT 23.05. Due to the small ROM size of 8MB I had to drop SSH server and some other packages from the firmware image.

To upload:
1. Hold reset and power the the device
2. Wait until the wifi LED is no longer blinking
3. Browse to 192.168.1.1
4. Upload the sysupgrade.bin image

Here are some images from the inside:

![2023-10-13-23-21-21-078](https://github.com/brupje/openwrt-comfast-ew74-v2/assets/2556592/1a8e675d-d2e9-438d-a2b3-472f1cc4d5af)

![2023-10-13-23-21-04-228](https://github.com/brupje/openwrt-comfast-ew74-v2/assets/2556592/d3208df1-7f5e-4832-b12c-87ed3c32c9bf)

![2023-10-13-23-21-11-872](https://github.com/brupje/openwrt-comfast-ew74-v2/assets/2556592/1461297c-4297-41ac-afd1-5b4d24934094)
