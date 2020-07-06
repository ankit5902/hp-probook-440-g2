# HP ProBook 440 G2 Hackintosh OpenCore
## System Specifications
  *  CPU : Intel(R) Core(TM) i5-5200U CPU @ 2.20GHz
  *  GPU : Intel HD Graphics 5500
  *  RAM : 8.00 GB (4 GB * 2)
  *  Motherboard : 
  *  Audio Codec : Realtek ALC282
  *  Ethernet Card : Realtek RTL8111 Gigabit Ethernet Controller 
  *  Wifi/BT Card : Broadcom BCM4352 802.11ac Wireless Network Adapter 
  *  Trackpad : Synaptics PS2 Trackpad
  *  Card Reader : Realtek RTS5227 PCI Express Card Reader

## Current version
* OpenCore - 0.5.9
* BIOS - M73 

## Disclaimer
This repository has no other purpose but sharing.
I want to share my hackintosh configuration for this particular laptop with the whole world.
This is not a step by step guide, rather a thing that can greatly help you on your way of turning this or similar laptop into a hackintosh.
Though you can just grab and use this if you have same or very similar laptop model, I greatly encourage you not do so, but instead read all the things I will mention below and get some knowledge.

## Gratitude
* [Hackintosh Reddit Community](https://www.reddit.com/r/hackintosh/) - for all the help and inspiration
* [Dortania](https://github.com/dortania) - for vanilla guides
* [Acidanthera](https://github.com/acidanthera) - for OC and lots of kexts
* [RehabMan](https://github.com/RehabMan) - for ACPI patching guides
* [Stonevil](https://github.com/stonevil) - for BIOS mods and hardware suggestions
* Vetz500, BlvckBytes & Takki - for original guide, help with battery, dGPU


## Where to begin
At the moment there is one main, up-to-date, generic hackintosh guide that is worthy of your attention - https://dortania.github.io/OpenCore-Desktop-Guide/, one trick with it that it is meant for desktop, and as you know we have a laptop here, so here's another one which is still work in progress https://dortania.github.io/vanilla-laptop-guide/.  
This hackintosh configuration has been made from scratch thanks to those guides, and you should be able to make it for yourself too. If in doubt, or something's not covered in there you can check with this repo's files while you go along.

## Specific Things
* **BIOS** You will have to change DVMT pre-alloc size to 64 MB
