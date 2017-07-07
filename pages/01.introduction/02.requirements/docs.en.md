---
title: Requirements
taxonomy:
    category:
        - docs
---

## Operating System Requirements

MedLaunch is built for Microsoft Windows only and has been tested on Windows 7/8/10. It will not work on Windows XP due to the .NET version it is built with.

A 64-bit operating system is preferred, although it should work after a fashion on 32-bit windows with some caveats:

* Sega Saturn games will not be playable (as the Windows builds of Mednafen only support Saturn in x86_64)
* The MedLaunch option to download the latest version of mednafen should NOT be used (as this is hard-coded to download the 64-bit releases of mednafen)
* MedLaunch has not been tested properly on 32-bit Windows - so do this at your own risk

## Software Requirements

MedLaunch is currently built using the [Microsoft .NET Framework 4.5.2](https://www.microsoft.com/en-gb/download/details.aspx?id=42643). You will need at least this version of .NET 4.5 installed for the application to launch.

## Hardware Requirements

* Mouse
* Keyboard
* (Optional) Gamepad/Joystick for Mednafen (although by default most controls are configured within Mednafen to be mapped to the keyboard

MedLaunch is currently a mouse and keyboard affair, with no current plans to implement gamepad control of the UI.

## System Firmware

For a number of emulated systems that Mednafen supports you will need specific BIOS/firmware dumps. From a legal standpoint, it is up to you to acquire these.

The will need to be placed either in the root of your Mednafen directory, the 'firmware' folder within your Mednafen directory, or another location that you can locate through MedLaunch (on a rom by rom basis).

The default ROMs that Mednafen looks for are shown below in the MedLaunch settings:
![](biosfirmware01.PNG)