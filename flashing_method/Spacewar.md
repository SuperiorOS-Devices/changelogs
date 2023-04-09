```
Device name: Nothing phone1
Device codename: Spacewar
Device maintainer: Vikas Yaduvanshi | OptimussPriime
```

---

# Method: #1

---

1. Download the ROM 
2. Boot into Recovery.
3. Go to Apply Update.
4. Sideload the ROM.
5. Wipe data.(*Check Note*) 
6. Reboot.

# Downloads:

* ROM: [Download](https://sourceforge.net/projects/superioros/files/Spacewar/)
* Flashing Files: [Download](https://sourceforge.net/projects/superioros/files/Spacewar/Flashing-files/)
* Boot Image: [Download](https://sourceforge.net/projects/superioros/files/Spacewar/Flashing-files/)


## Note:

* Always clean flash/ wipe data if you are coming from any other ROM or if you are coming from stock.
* Boot image ,Vendor_Boot image  only Needed  if you are coming from any other ROM.
* Check the changelog before flashing.


---
# Fastboot zip Flashing  Method: #2
---

Note : 
---
*Only Use This Method For Fastboot Flashing Zip*
---

Instructions for Clean flashing/Fresh installation 
1. Reboot to bootloader and proceed with following commands 
2. fastboot -w ( if you are coming from nos / any other rom / Superioros  too old )
3. fastboot update SuperiorOS*.zip
4.  Wait for the device to automatically reboot to fastbootd then to system 


---
Note : 
---
1. Backup all your important data as the clean installation will wipe your internal storage 
2.Make sure you have latest platform tools  [Download](https://developer.android.com/studio/releases/platform-tools) 
3.drivers installed ( not minimal official ones from google )

Note : 
* Don't try to dirty flash between  other roms
