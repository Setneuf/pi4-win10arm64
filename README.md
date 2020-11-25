# --- The image will be uploaded shortly ---

#
# WINDOWS 10 ARM64 for Raspberry Pi 4 2/4GB (FOR TESTING PURPOSES ONLY! NO OFFICIAL RELEASE FROM MICROSOFT)

This is a backup image of an working Windows 10 ARM64 on a Raspberry Pi 4 2GB/4GB (The 2 shown in the image). It is for be used with a 32GB mSD card (mininum) and I recomend at least an SanDisk Extreme UHS-I V30 microSDHC 32GB to be used. 

THIS IMAGE IS FOR TESTING PURPOSES ONLY!

![Screenshot](https://i.ibb.co/jMg1cX7/125549229-379558340051436-1087247185212036840-n.jpg)

#
#
## Installation

Just download the image and restore the backup to an mSD card with HDD Raw Copy (https://hddguru.com/software/HDD-Raw-Copy-Tool/).

After that plug your mSD card into the Pi4 and turn it on (and wait a bit for it, it's a little slow to startup...).

#
#
## How it was created

This image was created using the Windows on Raspberry tool available online (https://www.worproject.ml/) and the WoA-Installer-RPi (https://github.com/WOA-Project/WoA-Installer-Rpi/blob/master/Docs/GettingWoA.md), also available online, and has been a optimized a little bit (some services disabled, Windows Update disabled, Windows Defender disabled - but the firewall is still running off course... xD).

![Screenshot](https://i.ibb.co/Fn6TCfX/wor.jpg)

After using it for a while I can say to you guys that it's very stable and the x86 emulator works very well! In the image bellow you can see a Windows Forms app created in Visual Studio working as it should. I'm pretty satisfied for an not official and REALLY not optimized version of Windows 10 working on a Raspberry Pi 4 (it also works on the Pi 3, but it must be with an different image).

My PhD is related to IoT devices and i am really gonna use this Windows (TESTING ONLY!!) powered IoT device on it (along with other IoT devices and operating systems)

![Screenshot](https://i.ibb.co/BwxSvcH/123468020-360182455214655-664611567063342127-n.png)

On the 4GB Pi4 version it only uses/detects 3GB of RAM (the 2GB versions detects 2GB), but even so, it's very nice to have a desktop Windows on a Pi4. The network interface is working but the sound, wifi and bluetooth aren't (waiting for the master minds that made the port to put them working :D).

#
#
## Notes

I hope you enjoy the image and I repeat again, this is for TESTING PURPOSES ONLY, Microsoft does not have and official Windows 10 Arm64 for the Raspberry Pi yet and you will not be able to buy a cd-key to activate this Windows!

The tools used for creating this working Windows 10 Arm64 image weren't made by me, i just used the tools available on the WWW.


Please make sure to share your suggestions!
