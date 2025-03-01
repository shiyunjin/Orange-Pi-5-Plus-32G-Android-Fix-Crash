# Orange Pi 5 Plus 32G Android Fix Crash
The official firmware of Orange Pi 5 Plus 32G version all has design defects, which will cause random freezes, crashes, reboots and hibernation and freezing.

## Fixed the following issues
  * Random crashes ✅
  * Random restart ✅
  * Program randomly crashes ✅
  * External input is invalid ✅
  * Crash after suspend entry (deep) ❌ (Install [Magisk module](https://github.com/shiyunjin/Magisk-Android-Wake-Lock) to disable deep sleep)
  * ADB missing link library ✅

## Guide
  1. Please refer to the [official tutorial at this link](http://www.orangepi.org/orangepiwiki/index.php/Orange_Pi_5_Plus#How_to_use_RKDevTool_to_clear_SPIFlash) to step <b>n</b>, then install this document to continue.
  2. Right-click the menu and select Import

  ![](https://raw.githubusercontent.com/shiyunjin/Orange-Pi-5-Plus-32G-Android-Fix-Crash/main/img/1.png)

  3. Select rk3588_Android.cfg file to import
  4. Follow the steps in this picture to Flush Uboot.

  ![](https://raw.githubusercontent.com/shiyunjin/Orange-Pi-5-Plus-32G-Android-Fix-Crash/main/img/2.png)

  5. All Done. The machine will automatically start

