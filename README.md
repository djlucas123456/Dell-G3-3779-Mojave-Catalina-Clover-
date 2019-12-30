* 23.12.2019!! Update VoodooPS2 and Voodooi2C (Boot Kernel Panic Fix)

# Dell G3-3779 Hackintosh Mojave Clover

# Hardware Configuration
* i5 8300H 
* Iris UHD630 
* GTX1050
* Intel Wireless AC9462 
* ALC236 
* Realtek 8111 (Lan)

# Whats Working?

* WebCam

* UHD630

	- Full speed and Acceleration
	
* Battery

	- Functional calculation of the remaining time
	
* Screen

	- Functional automatic brightness when the charger is disconnected
	- Functional Night Shift
	- Correct determination of internal screen including picture
	- No 3 minute black screen!
	
* Audio

	- I didn't notice any mistake!
	- Functional internal microphone
	- Functional headphone port
	
* USB

	- Fully functional USB2 and USB3 at full speed

* System

	- Full CPU manager support
	- Added kext to correct memory pointer
	- Full speed SATA3 and NVMe SSD
	- Functional sleep mode when closed
	- Replace FAKESMC with VirtualSMC
	- Trackpad supports gestures. Works on VoodooI2C
	
# Untest or Not Working
* SD Reader 
* AC9462 WIFI (Must be replaced with DW1560 or DW1820a)
* GTX 1050 (blocked) 
* HDMI not work
