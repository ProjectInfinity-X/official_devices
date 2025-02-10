# Flash Infinity-X on Moto G82 5G (rhodep)

## Steps:

## 1. **Clean flash**

   - Download needed ROM images from https://sourceforge.net/projects/infinity-x/files/rhodep/15/recovery/
   - Download your preferred variant of Infinity-X on https://sourceforge.net/projects/infinity-x/files/rhodep/15/
   - When are you ready, reboot to bootloader.
   - Run these commands:

   ``` bash
   fastboot flash boot boot.img
   fastboot flash dtbo dtbo.img
   fastboot flash vendor_boot vendor_boot.img
   fastboot reboot recovery
   ```

   - When your device is on recovery mode, select Format Data and confirm.
   - Back to main menu and select Apply Update from ADB.
   - Open your terminal / CMD and run the following command:

   ``` bash
   adb sideload Project_Infinity-X*
   ```

   - Reboot the phone, and voila!

## 2. **Dirty Flash install**

   - You can use Updater app when any update is available for your device!
