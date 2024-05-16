<img align="right" src="https://github.com/Rubanoxd/Port-Windows-11-redmi-note-9_pro/blob/main/Miatoll.png" width="350" alt="Windows 11 Running On A Redmi Note 9 Pro / 9 Pro India / 10 Lite / 9S / 9 Pro max India / Poco M2 Pro">

# Running Windows on the Redmi Note 9 Pro / 9 Pro India / 10 Lite / 9S / 9 Pro max India / Poco M2 Pro

## Partitioning your device

### Prerequisites
- [Modded OFOX](https://github.com/Rubanoxd/Port-Windows-11-redmi-note-9_pro/releases/tag/modded-ofox)

- [ADB & Fastboot](https://developer.android.com/studio/releases/platform-tools)

- Brain (Very important)

### Notes:
> [!Warning]
> All your data will be erased! Back up now if needed.
>
> These commands have been tested.
>
> Do not run the same command twice
>
> DO NOT REBOOT YOUR PHONE if you think you made a mistake, ask for help in the [Telegram chat](https://t.me/woamiatoll)
>
> Do not run all commands at once, execute them in order!
>
> DO NOT MAKE ANY MISTAKE!!! YOU CAN BREAK YOUR DEVICE WITH THE COMMANDS BELOW IF YOU DO THEM WRONG!!!

### Flash OFOX recovery
> While in fastboot run
```cmd
fastboot flash recovery <ofox.img>
```

#### Run the partitioning script
> Replace **$** with the amount of storage you want Windows to have (do not add GB, just write the number)
> 
> If it asks you to run it once again, do so
```sh
adb shell partition $
```

#### Check if Android still starts
Just restart the phone, and see if Android still works


## [Next step: Installing Windows](2-install-en.md)
