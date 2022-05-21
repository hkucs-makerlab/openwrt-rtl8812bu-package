# rtl88x2bu package for OpenWRT
This was an attempt to get the driver for a USB3 Wifi adapter based on the rtl8812bu chipset.
  
Used driver: https://github.com/morrownr/88x2bu-20210702  
  
disclaimer: I have no idea what I'm doing. Use at your own risk.

## Usage
This is an OpenWRT package. Place this project's files in your OpenWRT source directory under `package/kernel/rtl88x2bu/` and run `make menuconfig` *from OpenWRT source directory* to include it in your build.  

## Kernel module parameters
Example: add ``88x2bu rtw_drv_log_level=0 rtw_led_ctrl=0`` to **/etc/modules.d/rtl88x2bu.conf**
