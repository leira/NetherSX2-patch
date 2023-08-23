# NetherSX2-patch
These are Unofficial companion scripts for NetherSX2 to expand on the amazing work already done by Anon and EZOnTheEyes

They aim to do the following:
* Remove the unnecessary ad services bloat left in the apk
* Fix the RetroAchievements Notifications
* Update the GameDB (which auto-magically applies game fixes), Controller Support, and the Widescreen and No-Interlace Patches
* Resign the APK using the original keystore used by AetherSX2 to remove the Play Protect Warning

The Update Script can also be used to reupdate the GameDB, Controller Support, and Widescreen and No-Interlace Patches at a later date

Note: This **ONLY** works with NetherSX2. They will break AetherSX2 if used with it

## Prerequisites
You only need: 
* Windows Vista or higher
* The [Java(TM) SE Development Kit](https://www.oracle.com/java/technologies/downloads/#jdk20-windows)
* A copy of the NetherSX2 APK (see below on how to build it yourself)
The rest comes prepackaged for your convience

## Getting a copy of the NetherSX2 APK
The best method is to use EZOnTheEyes' guide to build it yourself: <https://youtu.be/2y3uRlYq4SY>

## Using these scripts
Once you have a copy of the NetherSX2 APK named 15210-v1.5-4248-noads.apk, drop it in the same folder as remove-adservices.bat and update-files.bat
1. Run remove-adservices.bat to remove the Google Ad Services left in the APK - this will reduce the APK size by about 400KB 
2. Run update-files to apply the bug fixes and update the GameDB, Controller Support and Patches
3. Copy the now modified version of 15210-v1.5-4248-noads.apk back to your phone and install it using your File Manager

And there you go, you should now have an updated and bug fixed copy of NetherSX2 on your phone!

## Downloads
* You can grab a copy of these scripts [here](https://github.com/Trixarian/NetherSX2-patch/releases/download/1.2/NetherSX2-patch.zip)
* You can also use the [Patcher](https://github.com/Trixarian/NetherSX2-patch/releases/download/1.2/NetherSX2-Patcher.zip) to generate a copy of the NetherSX2 APK with the updates and bug fixes already applied on Windows systems
* [The xdelta file](https://github.com/Trixarian/NetherSX2-patch/releases/download/1.2/nethersx2.xdelta) can be grabbed for use with xdelta patchers on systems other than Windows
NOTE: No APKs are provided due to licensing issues. You have to build them yourselves using the above methods

## Credits
* PCSX2: <https://github.com/PCSX2/pcsx2> 
* AetherSX2: <https://www.aethersx2.com/archive/> 
* EZOnTheEyes: <https://www.youtube.com/@EZOnTheEyes> 
* Android build-tools: <https://androidsdkmanager.azurewebsites.net/Buildtools> 