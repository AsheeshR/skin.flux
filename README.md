skin.flux
=========

A work in progress skin for XBMC, customized for LumenEd devices (http://lumened.org/). It is a derivative of the XTV-SAF skin by Wyrm. 

The skin is being tested on XBMC v12 on Ubuntu 12.04 and current stable release of RaspBMC.

<h3>Installation</h3>

For XBMC running on Ubuntu:

- Download the zip file or clone the repository (approximately 15 MB)
- Extract the contents and change the folder name to `skin.flux`
- Paste the folder skin.flux in `~/.xbmc/addons/`
- Start XBMC and select Flux from Settings > Appearance

If the skin is not present or fails to load, then follow the install instructions for RaspBMC.

For RaspBMC installed on a SD card:

- Download the zip file or clone the repository (approximately 15 MB)
- Extract the contents and change the folder name to `skin.flux`
- Mount the SD card partitions
- Paste the folder `skin.flux` in `~/home/pi/.xbmc/addons` where `~` refers to mount point of RaspBMC, usually of the form `/media/<username>/mmc<>`.
- Start RaspBMC and select Flux from Settings > Appearance

For running videos, the following conditions have to be adhered to:

- USB drive must have the label VIDEOS
- The directory structure is `content/<subject>/<class>/` within the USB drive. Current support is for English, Hindi, Math and Computers, and classes 3, 4 and 5. 
- USB drive must be plugged in on boot/startup of RaspBMC/XBMC.



For any feedback and problems, please post on https://github.com/AsheeshR/skin.flux/issues
