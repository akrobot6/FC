# FC
Custom_FC
# Firmware Flashing

To flash Omnibus F7 V2:

1. Enter the bootloader mode: Hold press SW1 button and power the FC. 
2. Use Zadig to change the driver of STM Bootloader to WinUSB.
3. Switch off and on the FC to enter normal mode. In the device manager, you'd see the device under "Ports" as ... Virtual Com Port etc. 
4. Change the drivers of the Virtual Com to USB driver, generally found under in the microsoft folder.
5. After this change, one would see the device under USB devices.
6. Re-enter the bootloader mode, you would see that the port is listed as "DFU". 
7. After confirming this, download the firmware and flash. 
8. If the lord is with you, the above steps might work. Else Blue falcon will save you. 
