# Flash ROM on Xiaomi 11 Lite 5G NE | Mi 11 Le ( Lisa )

## Steps:

## 1. **First Time Install**

   - [Download Infinity Recovery](https://sourceforge.net/projects/infinity-x/files/lisa/14/recovery/)
   - Download boot, dtbo, vendor_boot & rom for your device from [here](https://sourceforge.net/projects/infinity-x/files/lisa/14/recovery/)
   - Reboot to bootloader
   - fastboot flash boot boot.img
   - fastboot flash dtbo dtbo.img
   - fastboot flash vendor_boot vendor_boot.img
   - fastboot reboot recovery
   - While in recovery, navigate to Factory reset -> Format data/factory reset and confirm to format the device
   - When done formatting, go back to the main menu and then navigate to Apply update -> Apply from ADB
   - adb sideload rom.zip replace "rom" with actual filename
   - optional:- Reboot to recovery fully to sideload any add-ons (e.g magisk)
   - Reboot to system


## 2. **Update ( Dirty Flash)**

   - Reboot to recovery
   - While in recovery, navigate to Apply update -> Apply from ADB
   - adb sideload rom.zip replace "rom" with actual filename
   - optional:- Reboot to recovery fully to sideload any add-ons (e.g magisk)
   - Reboot to system


## 3. **OTA**

   - Simply upgrade via ota updater (either if pushed or via local update import)
