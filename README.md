# Dell G3-3779 Hackintosh Mojave and Catalina Clover

* 12.04.2020!!

	- You can safely update to 10.15.4 through settings and updates
	  (just run the update and let everything go smoothly.)
	
	- Update Clover (5109)
	- Update Kext (Last version)
	- Change ALC Layout ID to 54 (fix sound after sleep)
	
* 22.01.2020!!	
	- added installer EFI folders on Mojave and Catalina
	- deleted unnecessary extra files.
	- Added DellSMBIOS Patch to config.plist. Improved NVRAM functionality and solutions to minor problems.
	
* 30.12.2019!!	You can update to Catalina via AppStore! Tried and everything functional and no problem. You can also use the. clover folder for a clean Catalina installation.

	I recommend to replace wifi card here video my work: https://www.youtube.com/watch?v=tED-_RBGmes&t=16s
	
	- bluetooth no problem even after sleep
	- Apple Watch unlock
	- Sidecar
	- Airdrop
	- Wifi 2,4Ghz, 5Ghz
	- you don't need any drivers or config.plist settings
	- etc...
	
* 23.12.2019!! Update VoodooPS2 and Voodooi2C (Boot Kernel Panic Fix)

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
* AC9462 WIFI (Must be replaced)
* GTX 1050 (blocked) 
* HDMI not work
