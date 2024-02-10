```
Device name: Motorola One Fusion+
Device codename: liber
Device maintainer: Dhinesh | cool585
```

# Clean flash Method:

# using boot image or superior recovery method
1. Download the ROM and boot-image.
2. Reboot to bootloader 
3. flash the bootimage (fastboot flash boot boot.img)
4. Reboot to recovery.
5. Wipe data.(*Check Note*)
6. Apply update via adb (adb sideload zip_name).
7. Reboot.

# using twrp

1. Download the ROM and official twrp or orangefox.
2. Reboot to bootloader
3. Fastboot boot twrp*.img
4. It will boot to twrp
5. Flash ROM or apply via adb
6. Wipe data
7. Reboot
# Downloads:

* ROM: [Download](https://sourceforge.net/projects/superioros/files/liber)
* SuperiorOS Recovery: [Download](https://sourceforge.net/projects/superioros/files/liber/recovery)

## Note:

* Always clean flash/ wipe data if you are coming from any other ROM or if you are coming from stock.
* Check the changelog before flashing.

### Vanilla users
* Don't forgot to flash GApps (Nik Core is recommended)
