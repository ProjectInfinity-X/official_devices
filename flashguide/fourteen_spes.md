# Flash ROM on Redmi Note 11 (Spes & Spesn)

## Steps:

1. **Boot into OrangeFox Recovery**
   - [Download OrangeFox Recovery](https://orangefox.download/device/spes)
  
2. **Wipe Data**
   - Select "Wipe"
   - Tick `data` (only if your device is not encrypted, or if it is encrypted with FDE)
   - Tick `cache`
   - Tick `dalvik`
   - **Important:** Do NOT wipe `system` or `vendor` unless specifically required as it might cause issues
   - For devices encrypted with FBE and changing ROMs:
     - Format data either before or after flashing the new ROM
     - For devices with A/B partitions: Format data both before and after flashing the new ROM
  
3. **Swipe to Wipe**
   - This will restore the installed ROM to a known state and remove incompatible apps/settings

4. **Select ROM to Flash**
   - From Internal Storage, SD Card, or OTG

5. **Swipe to Flash**

6. **Reboot OrangeFox Recovery**
   - Before doing anything else, reboot to ensure changes to partitions/filesystems take full effect

7. **Flash Additional Files**
   - Flash any other files you want (e.g., GAPPs, Magisk, etc.)

8. **Reboot Device**

9. **Initial Setup**
   - Wait for a long time while the new ROM sets itself up (go and make a cup of tea!)

10. **Enjoy**
   - Your device is now ready with the new ROM!