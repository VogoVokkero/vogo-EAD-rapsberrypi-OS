![Logo](icon.png)

# vogo-EAD-raspberrypi-OS
A public repository of Raspberry-Pi OS "Imager" compatible images

## Adding this repository to the Raspberry Pi Imager Tool

* Install Raspberry Pi Imager from https://downloads.raspberrypi.org/imager/imager_latest.exe
* In C:\Program Files (x86)\Raspberry Pi Imager, assuming this is your installation folder copy file [rpi-imager-vogo.cmd](rpi-imager-vogo.cmd) from this repo
* This shall provide VOGO images in Imager:

![Imager](imager.png)


## Adding New Images (VOGO)

* newly built images are first archived using "zip custom-os.img"
* then the compressed archived is added as a release though the "Draft a new release" interface.
* Update the file https://raw.githubusercontent.com/VogoVokkero/vogo-EAD-rapsberrypi-OS/refs/heads/main/os_list.json

