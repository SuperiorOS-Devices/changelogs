---
Device name: Google pixel 7a
Device codename: lynx
Device maintainer: Vikas Yaduvanshi 
---

### Declaration ###

---
 I am not responsible for bricked devices, dead SD cards,caused by you following
  these directions. YOU are choosing to make these modifications, and if
 you point your finger at me for messing up your device, .

---

# Method: #1 

---
If you already on superiorOS then follow this Method , IF NOT THEN FOLLOW # Method2
---

1. Download the Recovery flashing zip   from Here [Download](https://sourceforge.net/projects/superioros/files/lynx/gapps/)
2. Boot into Recovery.
3. Go to Apply Update.
4. Sideload the ROM.
5. Wipe data.(*if you want to clean flash this rom *) 
6. Reboot.

 
---
# Method: #2 flash all files manually 
* always use latest platform tools From here [Download]((https://developer.android.com/tools/releases/platform-tools/)

# Downloads:
following files:- From Here: [Download](https://sourceforge.net/projects/superioros/files/lynx/images/)

```
boot.img
dtbo.img
vendor_kernel_boot.img
vendor_boot.img
```




*Reboot to bootloader keep in mind bootloader should be unlocked
* connect your devive to pc  then open cmd 
# FLASH the downloaded image files to your device by typing 

```
fastboot flash boot boot.img
fastboot flash dtbo dtbo.img
fastboot flash vendor_kernel_boot vendor_kernel_boot.img
fastboot flash vendor_boot vendor_boot.img

```

## reboot to SuperiorOS recovery
*  If you are not in recovery, reboot into recovery:
*  in bootloder menu choose boot to recovery option.


once superior recovery up choose Factory Reset option under advanced settings 
 then Format data / factory reset and continue with the formatting process. 
This will remove encryption and delete all files stored in the internal storage, as well as format your cache partition (if you have one).
 Return to the main menu.
 
 ```
Sideload the SuperiorOS .zip package but do not reboot before you read/followed the rest of the instructions!
On the device, select “Apply Update”, then “Apply from ADB” to begin sideload.
 On the host machine, sideload the package using: adb sideload filename.zip
```

# Fastboot zip Flashing  Method: #3


Note : 
---
*Only Use This Method For Fastboot Flashing Zip*  : [Download](https://sourceforge.net/projects/superioros/files/lynx/images/)

---
Instructions for Clean flashing/Fresh installation 
1. Reboot to bootloader and proceed with following commands 
2. fastboot -w ( if you are coming from stock os  any other rom / Superioros  too old )
3. fastboot update SuperiorOS*.zip
4. Wait for the device to automatically reboot to fastbootd then to system 

---
Note : 
---
1. Backup all your important data as the clean installation will wipe your internal storage 
2.Make sure you have latest platform tools  [Download](https://developer.android.com/studio/releases/platform-tools) 
3.drivers installed ( not minimal official ones from google )

## Note:

* Always clean flash/ wipe data if you are coming from any other ROM or if you are coming from stock.
*  always use latest platform tools 
* Check the changelog before flashing.
