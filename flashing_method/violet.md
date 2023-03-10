```
Device name: Xiaomi Redmi Note 7 Pro
Device codename: violet
Device maintainer: Nipin NA | Joker-V2
```

# Method:

## Encryption (Clean flash)

1. Download the ROM 
2. Download SuperiorOS Recovery
3. Boot into fastboot mode
4. Flash recovery (`fastboot flash recovery recovery.img`)
5. Boot into SuperiorOS Recovery (`Long press volume up + power button`)
6. Tap on Apply Update option
7. Side load rom (`adb sideload rom.zip`)
8. Format data
7. Reboot into System

## Encryption (Dirty flash)
1. Download the Update
2. Boot into SuperiorOS Recovery
3. Tap on Apply Update option
4. Side load rom (`adb sideload rom.zip`)
5. Reboot into System

## Decryption (Clean flash)

1. Download the ROM 
2. Download any A13 supported Recovery
3. Boot into fastboot mode
4. Flash recovery (`fastboot flash recovery recovery.img`)
5. Boot into Recovery (`Long press volume up + power button`)
6. Flash ROM
7. Flash encryption disabler 
8. Reboot into System

## Decryption (Dirty flash)

1. Download the ROM 
2. Boot into Recovery
3. Flash ROM
4. Flash encryption disabler 
5. Reboot into System

# Downloads:

* ROM: [Download](https://sourceforge.net/projects/superioros/files/violet)
* SuperiorOS Recovery: [Download](https://sourceforge.net/projects/superioros/files/violet/recovery)
* TWRP Recovery: [Download](https://sourceforge.net/projects/joker-builds/files/TWRP/A13/recovery.img/download)
* Encryption disabler: [Download](https://t.me/superioros_violet/60824)

## Note

### Vanilla users
* Don't forgot to flash GApps (Nik Core is recommended)
* Only flash GApps on clean flash (No need to flash GApps after each updates)
