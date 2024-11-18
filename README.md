# Rogue Outcast 2 Beam

## Software Versions

[V1.240829 - Rogue Outcast 2 Beam](https://github.com/Chauvet-Pro/ROGUEOUTCAST2BEAM/blob/38842cc760d919542d3f67fcafd1c17783b54f7c/firmware/V1.240829.zip)
- Added auto screen reverse

[V1.240401 - Rogue Outcast 2 Beam](https://github.com/Chauvet-Pro/ROGUEOUTCAST2BEAM/blob/530941d3f23e52bb6cc65320bd884280c96d0d9a/firmware/V1.240401.zip)
- Fixed static gobo wheel issue
     * Issue: Static gobo wheel will lose steps if reset is required from the console while the wheel is doing color scroll.

[V1.230803 - Rogue Outcast 2 Beam](https://github.com/Chauvet-Pro/ROGUEOUTCAST2BEAM/blob/530941d3f23e52bb6cc65320bd884280c96d0d9a/firmware/V1.230803.zip)
- Improved shutter effect

[V1.230302 - Rogue Outcast 2 Beam](https://github.com/Chauvet-Pro/ROGUEOUTCAST2BEAM/blob/530941d3f23e52bb6cc65320bd884280c96d0d9a/firmware/V1.230302.zip)
- Revised for full compatibility with fixtures that have old IC

[V1.221017 - Rogue Outcast 2 Beam](https://github.com/Chauvet-Pro/ROGUEOUTCAST2BEAM/blob/530941d3f23e52bb6cc65320bd884280c96d0d9a/firmware/V1.221017.zip)
- Released software version

&nbsp;

## USB Software Update Instructions
1.  Power on the product and plug the flash drive into the USB port.
2.	Once the flash drive has been detected, the message “***USB Update***” will be displayed. Press **< YES >**.
3.	The next screen will show the software versions available for this fixture on the USB drive. For multiple versions of the software for the same fixture, use **< UP >** or **< DOWN >** to select the desired version. Press **< ENTER >**.
4.	The ***"USB Update*** screen will re-appear. Press **< YES >**.
5.	The upgrade will start. DO NOT turn off the power or disconnect the USB while the USB LED is still blinking during the process. The screen display will read: ***"USB Update Wait"***. USB update can take several minutes to complete.
    > When the USB stops blinking, all the motors will power down, and the display will go blank. DO NOT turn off the power. The fixture will automatically reboot when the update is done.
6.  Go to **Sys Info** on the fixture's menu map and confirm the firmware revision.
7.	When the boot-up process is finished, restart the fixture.


### Special Notes
* Place the .chl file in the root directory of the USB drive.
* The product's USB port supports up to 32GB capacity and only works with FAT32 file format.
* Turning off the power or removing the USB while still blinking during the update will cause partial or total firmware failure in the targeted fixture(s). If this occurs, the user will need the **UPLOAD 08** device to fix this. 
