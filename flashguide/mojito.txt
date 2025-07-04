# Flashing Method: Project_Infinity-X (mojito)

- [Download Mojito Recovery Tools](https://sourceforge.net/projects/infinity-x/files/mojito/recovery_images/)

Clean Flash:

1. Direct boot to OFOX recovery - In fastboot mode use command ```fastboot boot OFOX.img```
2. Flash PBRP Recovery zip then Reboot to PBRP Recovery
3. Format data
4. Reboot to recovery
5. Flash latest firmware
6. Reboot to recovery
7. Now, Flash ROM
8. Flash PBRP Recovery zip
9. Reboot to recovery
10. Flash Gapps zip (For Vanilla user who wants flash nikgapps)
11. Reboot to system
  
DIRTY FLASH:

1. Reboot to PBRP Recovery
2. Now, Flash ROM
3. Flash PBRP Recovery zip
4. Reboot to recovery
5. Flash Gapps zip (For Vanilla user who wants flash nikgapps)
6. Reboot to system
