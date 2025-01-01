# gta4ljt-bl
`BL`, `CP` files from stock firmware files for manual bootloader upgrade when running a custom rom

## BEFORE ANYTHING
Files here are from the stock unmodified ROM (aka. Firmware) for the device **Samsung Galaxy Tab A7 10.4" (2020) (LTE)** with the model number of `SM-T505N`, **DO NOT ATTEMPT TO FLASH ANY FILES FROM HERE IF YOUR MODEL NUMBER DOESN'T MATCH.(even if it's just a letter difference)**

You will need to use files here if you want (for example) to upgrade the bootloader version of your Tab A7 10.4" (2020) (LTE) with the codename of `gta4ljt` and model number of `SM-T505N` to the latest bootloader version without the need to do a full odin restore (back to stock) when you have a custom rom installed on your device.

## General instructions as follows
* Fully power off your tablet.(long press power button and tap power off twice)

* Reboot device into download mode. (hold both volume buttons and plug in usb cable then let go of all buttons when screen turns on and press volume up)

* Open odin (recommended v3.14.4 at least)

* Put AP,CP into their respective slots.

* make sure repartition is NOT enabled and erase NAND is NOT enabled too. (check them in options tab)

* press Start and once flashing finishes you have successfully upgraded your firmware!

## Why this repo while others exist?
Other custom roms for this device `gta4ljt` does only provide bootloader files for the `gta4l` device (`SM-T505`) so if you don't want to convert your device from `SM-T505N` to `SM-T505` or run into issues while wanting to upgrade bootloader just use this one.
