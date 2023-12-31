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

```

First time installation:
```

1. You must have superior recovery installed ( fastboot flash vendor_boot vendor_boot.img)
2. Boot superior recovery
3. Format Data
4. Plug your phone to pc and Apply update via ADB
5. Run adb sideload <drag_crdroid_zip_here>
6. Reboot

```

Update installation:
```

1. You must have crDroid recovery installed ( fastboot flash vendor_boot vendor_boot.img )
2. Boot crDroid recovery
3. Plug your phone to pc and Apply update via ADB
4. Run adb sideload <drag_crdroid_zip_here>
5.Reboot

```


NOTE: If all the flashing process succeeds the terminal output will stop at 47% and report adb: failed to read command: Success. In some cases it will report adb: failed to read command: No error which is also fine. Also gapps are included by default with the rom.
```

 

```

# Fastboot zip Flashing  Method: #2
```



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
