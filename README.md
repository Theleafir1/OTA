# AxionOS

## Realme gt master edition [RMX3360/61/63]

## Flashing Instructions

<b>To install AxionOS on the Realme GT Master Edition (codename: lunaa), follow these steps:</b>

1. Download Recovery
- Download the [los Recovery](
  https://sourceforge.net/projects/axionos-lunaa/files/Recovery/recovery.zip/download) file and extract it to a folder on your computer.

2. Flash the Recovery
- On Linux: Run the `flash.sh` script.
- On Windows: Run the `flash.bat`script.
This will flash the recovery and automatically boot your device into the recovery mode.

3. Wipe Data
In the recovery menu, select "Wipe data/factory reset" to clear existing data on the device.

4. Sideload AxionOS
Use the following command in a terminal or command prompt to sideload the AxionOS zip file:

```
adb sideload <path-to-filename.zip>
```

5. Wait for Completion
The sideload process will progress to 47% before finishing. This is normal—be patient until it completes.

6. Reboot
Once the sideload is done, select "Reboot system now" from the recovery menu. Congratulations! You’ve successfully flashed AxionOS!

## Dirty Flash

1. Reboot to Recovery 

2. Sideload AxionOS
Use the following command in a terminal or command prompt to sideload the AxionOS zip file:

``` 
adb sideload <path-to-filename.zip>
```

3. Wait for Completion
The sideload process will progress to 47% before finishing. This is normal—be patient until it completes.

4. Reboot
Once the sideload is done, select "Reboot system now" from the recovery menu. Congratulations! You’ve successfully flashed AxionOS!

## Notes

- Always back up your data before starting the installation. 
