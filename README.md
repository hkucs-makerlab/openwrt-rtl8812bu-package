# rtl88x2bu package for OpenWRT
This was an attempt to get the driver for a USB3 Wifi adapter based on the **rtl8812bu** chipset.
  
**Tip: [select branch](https://github.com/erintera/openwrt-rtl8812bu-package/branches) for OpenWRT version you're using.**  
  
Used driver: https://github.com/morrownr/88x2bu-20210702  
Thanks to [Jason](https://gitlab.com/_jason/openwrt-rtl8812bu-package)  
This was created using the rtl8812au-ct package as a guide (but it's not for 8812au!)  
  
*disclaimer: I have no idea what I'm doing. Use at your own risk.*

## Usage
This is an OpenWRT package. Place this project's files in your OpenWRT source directory under `package/kernel/rtl88x2bu/` and run `make menuconfig` *from OpenWRT source directory* to include it in your build.  

## Kernel module parameters (for advanced users)
Example: add ``88x2bu rtw_drv_log_level=0 rtw_led_ctrl=0`` to **/etc/modules.d/rtl88x2bu.conf**
