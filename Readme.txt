Building the bootloader for the LilyPadUSB
0. Make sure you've got an AVR-based DI-Lambda. Does the chip read ATMAGE32u4? You are good. Not sure - ask us.
1. Download the LUFA-111009 file (http://fourwalledcubicle.com/blog/2011/10/lufa-111009-released/).
2. Extract that file directly to the DI-Lambda-bootloader-avr  directory.
3. Open a command prompt in the DI-Lambda-bootloader-avr bootloader directory.
4. Type 'make'.
5. Enjoy!

Programming the bootloader for AVR-based DI-Lambda
1. Open a command prompt in the DI-Lambda-bootloader-avr folder.
2. Connect your programmer- use a 2x3 .1" header, pressed against the programming vias.
3. Check the Makefile. It assumed you are using the "Arduino as ISP" programmer on USB port /dev/ttyACM0. Change it it's not correct for you.
4. Type 'make program' into the command prompt.
