* 30.12.2019!!	You can update to Catalina via AppStore! Tried and everything functional and no problem. You can also use the. clover folder for a clean Catalina installation.

I recommend to replace wifi card here video my work: https://www.youtube.com/watch?v=tED-_RBGmes&t=16s
	
	- bluetooth no problem even after sleep
	- Apple Watch unlock
	- Sidecar
	- Wifi 2,4Ghz, 5Ghz
	- you don't need any drivers or config.plist settings
	
* 23.12.2019!! Update VoodooPS2 and Voodooi2C (Boot Kernel Panic Fix)

# Dell G3-3779 Hackintosh Mojave and Catalina Clover

# Hardware Configuration
* i5 8300H 
* Iris UHD630 
* GTX 1050
* Intel Wireless AC9462 
* ALC236 
* Realtek 8111 (Lan)
* No USB-C

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
