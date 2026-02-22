# [Arcade: SEGA System 1](https://www.system16.com/hardware.php?id=693) and [2](https://www.system16.com/hardware.php?id=694) for the [MiSTer](https://github.com/MiSTer-devel/Main_MiSTer/wiki)

by [MiSTer-X](https://twitter.com/mrx_8b) and [blackwine](https://x.com/blk_yn)

## Specifications

* T80/T80s - Version : 0242
* Z80 compatible microprocessor core - Copyright (c) 2001-2002 Daniel Wallner (jesus@opencores.org)
* 2020/01/08  Impl. Trigger 3  (for SEGA Ninja)

## Supported Games

Because this is a fork of the existing [MiSTer System 1 Core](https://github.com/MiSTer-devel/Arcade-SEGASYS1_MiSTer) duplicated titles have been removed. 

Non-duplicated System 1 titles supported by this core:

* Brain
* Gardia
* Heavy Metal
* Noboranka / Zippy Bug (bootleg)

SEGA System 2 titles supported by this core:

* Choplifter
* DakkoChan House

Sega System 2 games currently **not yet** supported:

* 119
* Senryaku Game Bopeep
* Shooting Master
* Warball

## High score save/load

* To save your scores use the 'Save Settings' option in the OSD
* All games supported except Brain, Choplifter, Gardia, Heavy Metal, Water Match and Wonder Boy.

## Installation

Add the following to your `downloader.ini` file.

```ini
[TheJesusFish/Blackwine-Segasystem1-2_Mister]
db_url = https://raw.githubusercontent.com/TheJesusFish/Blackwine-SegaSystem1-2_MiSTer/db/db.json.zip
```
