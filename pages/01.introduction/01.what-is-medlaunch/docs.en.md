---
title: 'What is MedLaunch?'
taxonomy:
    category:
        - docs
---

MedLaunch is an open source ([MIT](https://github.com/Asnivor/MedLaunch/blob/master/MedLaunch/LICENSE)) Windows frontend for the multi-system emulator, [Mednafen](https://mednafen.github.io/).

![MedLaunch Games Library](gl01.PNG?lightbox=1024&cropResize=700)

## So What is Mednafen?

Mednafen is an open source ([GNU GPLv2)](http://www.gnu.org/licenses/gpl-2.0.html) cross-platform command-line-driven (no UI) multi-system emulator that currently emulates the following systems:

* Atari Lynx
* Neo Geo Pocket (and Pocket Color)
* Bandai WonderSwan
* Nintendo GameBoy (and GameBoy Color)
* Nintendo GameBoy Advance
* Nintendo Entertainment System/Famicom Disk System
* Super Nintendo Entertainment System/Super Famicom
* Nintendo Virtual Boy
* NEC PC Engine/TurboGrafx 16 (and PCE-CD)
* NEC SuperGrafx
* NEC PC-FX
* Sega Game Gear
* Sega Genesis/Megadrive
* Sega Master System
* Sega Saturn (experimental, x86_64 only)
* Sony PlayStation (PSX)

For most emulated systems it supports save states and real-time game rewinding.

## So Why Do I Need a Frontend?

You don't. But most people will find a frontend easier.

Mednafen is launched from the command-line and utilises config txt files. Without a frontend you have to edit the config file(s) manually and launch mednafen from the command-line every time specifying the path to the ROM/Disc Image that you wish to run. Or you can create batch files for each game.

## MedLaunch Features

* No installation required (and all data is kept in the MedLaunch directory)
* Responsive Metro UI
* Local (SQLite) auto-generated database where all settings are saved
* Supports Mednafen versions 0.9.39.x through to the latest
* Nearly all Mednafen command line parameters available and configurable
* Mednafen controller configuration available using DirectInput and XInput (changes are saved directly to the mednafen config file rather than MedLaunch database)
* Built-in games library (with system filters and dynamic search)
* ROM scanner (for games library import) with NOINTRO/TOSEC matching
* Manual and Auto disc import (disc games must be in their own sub-folders within the system (PSX, SS, PCFX or PCECD) folder)
* DISC scanner (for games library import) with custom DAT matching based on game serial number (detected from disc image)
* Auto-M3U platlist generation for multi-disc games
* Supports the usual Mednafen rom and disc formats
* Supports multiple ROM files per archive (7zip and zip) - (no archives within archives and no subfolders within the archive)
* Games library sidebar for game info, stats and media (with the option to hide certain columns on a per-system basis)
* Scraping of game data and media from thegamesdb.net and mobygames
* Built-in netplay server selection
* Built-in browser control with links to Mednafen help pages
* Ability to hide mednafen cores completely 
* Customizable color scheme