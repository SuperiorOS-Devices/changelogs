```
Device name: Pocophone F1
Device codename: beryllium
Device maintainer: Akshat
```

# Downloads:

* Recovery: [Download](https://sourceforge.net/projects/berylliu020/files/images/recovery.img/download)
* Super_empty image: [Download](https://sourceforge.net/projects/berylliu020/files/images/super_empty.img/download)

## IMPORTANT TO NOTE:

* Do not try to switch to any other kernel than stock or radioactive v2.

* Do not use any other recovery than SuperiorOS recovery or Orangefox Dynamic recovery.

* You must format data with given SuperiorOS recovery or Orangefox Dynamic recovery.


* You must clean flash in following cases-:

- You are coming from any other ROM or MIUI

- You are coming from previous Android Version

- You are coming from Non Retrofit Dynamic ROM


# Clean Flash (coming from a different ROM)

Clean flash involves formatting data which means you will be loosing data stored in the internal storage of your device, data in SD Card should not be affected. I will not be responsible for any loss of data.

1. Download ROM, recovery and super_empty files to your computer

2. Reboot the device to bootloader (Fastboot Mode)

3. Flash empty super image by running fastboot wipe-super <path/to/super_empty.img> in terminal

4. Flash recovery image by running fastboot flash recovery <path/to/recovery.img> in terminal

5. Reboot to recovery mode

6. Go to main menu > Factory reset > Format data/factory reset > Format data - Back to Main menu

7. Reboot to recovery mode again

8. On your phone [which is in recovery mode], Apply update > Apply from ADB

Flash the ROM through ADB sideload by running adb sideload <path/to/rom.zip> in terminal

9. Reboot


# Dirty Flash / Update

There will be no loss of data if everything goes well. Keep backups incase of any mishap. I will not be responsible for any loss of data.

1. Download ROM file to your computer

2. Reboot the device to recovery

3. On your phone [which is in recovery mode], Apply update > Apply from ADB

4. Flash the ROM through ADB sideload by running adb sideload <path/to/rom.zip> in terminal

5. Reboot


# OTA
Use the built-in Updater ("Settings > System > Updater") to apply OTA updates as they become available.


## NOTES

- If you get the following error: fastboot: usage: unknown command wipe-super, make sure ADB and fastboot are updated to the latest version. You need fastboot version 28.0.2 or greater.
