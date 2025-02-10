# Flash Infinity-X on Motorola Edge 30 (dubai)

## Steps:

## 1. **First Time Install**

   - Download needed ROM images from https://sourceforge.net/projects/infinity-x/files/dubai/14/recovery/
   - Download your preferred variant of Infinity-X on https://sourceforge.net/projects/infinity-x/files/dubai/14/
   - When are you ready, reboot to bootloader.
   - Run these commands:

   ``` bash
   fastboot flash boot boot.img
   fastboot flash dtbo dtbo.img
   fastboot flash vendor_boot vendor_boot.img
   fastboot reboot recovery
   ```

   - When your device is on recovery mode, select Format Data and confirm.
   - * First ROM on your device? First, flash copy-partitions zip, for your security! https://mirrorbits.lineageos.org/tools/copy-partitions-20220613-signed.zip
   - * After installed copy-partitions, back to main menu and go to Advanced > Reboot to recovery, after, you can follow the instructions.
   - Back to main menu and select Apply Update from ADB.
   - Open your terminal / CMD and run the following command:

   ``` bash
   adb -d sideload Project_Infinity-X*
   ```

   - Reboot the phone, and voila!

## 2. **Dirty Flash install**

   - You can use Updater app when any update is available for your device!
