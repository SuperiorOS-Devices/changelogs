```
Device name: Google Pixel 7
Device codename: panther
Device maintainer: Jayant Deshmukh | jd1811
```

# Method:

1. Download the build and corresponding recovery files of the month.
2. Reboot to bootloader.
3. Unzip the recovery files and execute the following files
* fastboot flash boot boot.img
* fastboot flash dtbo dtbo.img
* fastboot flash vendor_kernel_boot vendor_kernel_boot.img
* fastboot flash vendor_boot vendor_boot.img
4. Reboot to recovery and factory reset the device.
5. adb sideload {zip_name}
6. Reboot

# Downloads:

* ROM: [Download](https://www.pling.com/p/1908484)

## Note:

* Always clean flash/ wipe data if you are coming from any other ROM or if you are coming from stock.
* Check the changelog before flashing.
