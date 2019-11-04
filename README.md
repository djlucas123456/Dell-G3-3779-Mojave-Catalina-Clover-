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
	- Trackpad supports gestures. Works on VoodooI2C (If you have trouble booting the system. Delete the VoodooI2C + VoodooI2CHID files from the Clover-Kext-Others folder). Trackpad works better on VoodooI2C than on VoodooPS2Controller
	
# Untest or Not Working
* SD Reader 
* AC9462 WIFI (Must be replaced with DW1560 or DW1820a)
* GTX1060(blocked) 

# Known Issue
* I haven't tried HDMI
* Trackpad with VoodooI2C drivers is still in solution to avoid panic kernel! But I have to say that it works fine for me now.
