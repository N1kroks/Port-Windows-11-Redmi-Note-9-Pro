<img align="right" src="https://github.com/Rubanoxd/Port-Windows-11-redmi-note-9_pro/blob/main/Miatoll.png" width="350" alt="Windows 11 Running On A Redmi Note 9 Pro">

# Running Windows on the Redmi Note 9 Pro

## Troubleshooting Issues
> Below you will find a list of common problems and their solutions

## Cannot mount Windows in Android
If mounting Windows produces an empty folder, you either don't have Windows installed, or your rom does not have mount support.

##### Finished!

## Cannot write to Windows in Android
> This is caused by shutting down Windows instead of restarting it.
- To solve this, boot to Windows and then press "restart", then as the screen shuts off boot to TWRP and from there load up Android.
- Or, disable hibernation in Windows using [this](https://github.com/n00b69/woa-beryllium/releases/tag/1.0) script 
> Alternatively, if you have already set up the Switch to Android app, simply use this to switch to Android.

##### Finished!

## USB does not work
Run [USB Host Control](https://github.com/erdilS/Port-Windows-11-Xiaomi-Pad-5/releases/tag/USBHost) to enable/disable USB host mode and confirm that you want to disable/enable USB host mode.

##### Finished!

## DISM Error:87 The add-driver option is unkown
This usually means that you have an unclean Windows image with some other drivers. You need to get a clean Windows image (which means you didn't follow instructions).

##### Finished!

## 0xc000021a BSOD
This usually means that winlogon.exe has failed, and you may need to reapply the Windows image.

##### Finished!

## The computer restarted unexpectedly or encountered an unexpected error
If you stumble upon this error, you may need to redeploy the Windows image. Use the [reinstall guide](reinstall-en.md) for this.

##### Finished!

## INACCESSIBLE_BOOT_DEVICE BSOD
This Blue Screen of Death likely means some broken driver installation. To fix this, reinstall the drivers using the [reinstall guide](reinstall-en.md).

##### Finished!

## Device can boot into android but not bootloader
This is caused by partitions with volume names the bootloader cannot handle, to fix this:

- Boot to recovery

- Connect phone to PC

- Open cmd on PC

- Run ```adb shell```

- Run ```parted```

- Run ```print``` to list all partitions

- Look for partitions that have spaces in the names e.g "Basic Data Partition" and note their volume number

- Now run ```rm <vol number>``` e.g ```rm 36```

##### Finished!

## Touchscreen doesnt work
- Turn display off and on

##### Finished!


















