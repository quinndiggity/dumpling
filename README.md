<p align="center">
  <img src="assets/dumpling-logo.png" alt="Dumpling Logo" width="80" height="80">

  <h3 align="center">Dumpling</h3>

  <p align="center">
    A simple, all-in-one Wii U file dumper! Developed with the intent of making dumping games and other files for Cemu faster and easier.
  </p>
</p>

## How to install
**Method 1:**  
Use the Wii U App Store to download and install it in the homebrew launcher. See Dumpling's page [here](https://apps.fortheusers.org/wiiu/dumpling).

**Method 2:**  
Download the [latest release from Github](https://github.com/emiyl/dumpling/releases), and extract the `dumpling.zip` file to the root of your SD card.

## How to use
Using it just requires you to open up the homebrew launcher and launch the app. No Mocha or Haxchi required!

For an always up-to-date guide to dump your games for Cemu using Dumpling, see [cemu.cfw.guide](https://cemu.cfw.guide/dumping-games)! It also goes through the steps of installing and running homebrew and Dumpling for the first time!


## How to compile
- Install [DevkitPro](https://devkitpro.org/wiki/Getting_Started) for your platform.
- Install [wut](https://github.com/devkitPro/wut) through DevkitPro's pacman or compile (and install) the latest source yourself.
- Compile [libiosuhax](https://github.com/yawut/libiosuhax#using-wut---static-library) from source yourself as a static library.
- Compile [libfat](https://github.com/Crementif/libfat) from source, since it has been fixed to perform MUCH better in certain situations which would normally cripple the classic Dumpling.
- Then, with all those dependencies installed, you can just run `make` to get the .rpx file that you can run on your Wii U.


## Features
- Dumps everything related to your games! Game, updates, DLC and saves are all dumpable!
- Dumps both disc and digital games in an extracted format, making for easy modding and usage with Cemu.
- Creates 1:1 copies of data with proper meta data.
- Allows dumping to an SD or USB stick/drive (must be formatted as fat32).
- Allows you to dump system applications too.
- Feature to quickly dump everything needed to play online with Cemu, including the otp.bin and seeprom.bin!
- Also dumps extra compatibility files for Cemu when dumping online files.
- Has features to dump the base game files, update files and DLC files separately.

## Credits
- [Crementif](https://github.com/Crementif) for [dumpling-rework](https://github.com/emiyl/dumpling)
- [emiyl](https://github.com/emiyl) for [dumpling-classic](https://github.com/emiyl/dumpling-classic)
- chrissie for testing
- FIX94, Maschell and Quarky for making and maintaining homebrew (libraries)
- smea, plutoo, yellows8, naehrwert, derrek, dimok and kanye_west for help making exploits and CFW possible