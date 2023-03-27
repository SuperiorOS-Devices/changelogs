```
Device name: Motorola Edge 30
Device codename: Dubai
Device maintainer: Jayant Deshmukh | jd1811
```

# Clean flash Method:

1. Download the ROM and boot-images.zip.
2. Extract the boot-images.zip
3. Reboot to bootloader and flash the bootimages to respective partitions (boot, vendor_boot, dtbo).
4. Reboot to recovery.
5. Wipe data.(*Check Note*)
6. Apply update via adb (adb sideload zip_name).
7. Reboot.

# Downloads:

* ROM: [Download](https://www.pling.com/p/1908484)
* Boot Image: [Download](https://www.pling.com/p/1908484)

## Note:

* Always clean flash/ wipe data if you are coming from any other ROM or if you are coming from stock.
* Check the changelog before flashing.