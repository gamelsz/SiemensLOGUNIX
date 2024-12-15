# Siemens LOGOSoft on Linux installation guide

This guide is made for people looking for installing a Siemens LOGO Soft Comfort on Unix based system
Everything showed in this guide was made on Arch Linux based system, and most of the rules should apply to other system with minor commands tweaks.

## 1. Get a LOGO
I  won't provide a source here, you have to get it on your own (of course you have to buy it)

## 2. Install Wine && Winetricks
Use "$ sudo pacman -S wine" and "$ sudo pacman -S winetricks" for Arch based systems
Run the Winetricks once
Get into terminal, choose the LOGO installer path and type "wine *.exe" where * is your file name.
Simply install the LOGO using wine.

## Known problems
1. You will have to configure the Ethernet connection on your own
2. Direct COM and USB connection is under testing 
 
