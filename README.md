# Home Infrastructure
Just an Aussie Bloke trying to help other like minded IT nuts setup similar IT infrastructure in their own environments/homes/offices.

# Objectives
I want to start my Home Assistant journey and setup little projects around the house.
I currently have setup a Smart Garage Door using an ESP8266 and magnetic switch.

# Infrastructure Design
I wanted to setup a raspberry pi and host most (if not all of) my applications within it via docker.  
The conditions of my containers must host the following applications,  
- mqtt broker
- Home Assistant

# Resources:  
### Hardware  
_All Australian Stores_  

**Core Infrastructure**
| Hardware                  | Price | Store                                                                                 |
| ------------------------- | ----- | ------------------------------------------------------------------------------------- |
| Raspberry Pi 4 Model B 8GB Starter Kit | $252 |[PiAustralia](https://raspberry.piaustralia.com.au/products/raspberry-pi-starter-kit) |  

_Note: You can use any Raspberry Pi or second hand computer off marketplace_

**Garage Door Project**  
| Hardware                  | Price | Store                                                                                 |
| ------------------------- | ----- | ------------------------------------------------------------------------------------- |
| ESP8266 NodeMCU V2 CP2102: | ~$5 | [AliExpress](https://www.aliexpress.com/item/1005001636634198.html?spm=a2g0o.order_list.0.0.6d9818022rGaHn) |  
| 5V Relay Switch: | $7.95 | [Altronics](https://www.altronics.com.au/p/z6422-5v-2-channel-relay-control-module/) |  
| Magnetic Sensor: | $13.50 | [Altronics](https://www.altronics.com.au/p/s5153-spdt-surface-mount-security-magnetic-reed-switch/) |  

## Software  
Powershell: for SSH into the Raspberry Pi  
**Inbuilt within the Windows OS**  
KeePassXC: for storing all my Passwords encrypted locally - Local/Safe/Secure  
[Link](https://keepassxc.org/download/#windows)  
RaspianOS: host os for raspberry Pi  
[Link](https://downloads.raspberrypi.org/imager/imager_latest.exe)  
NodeMCU Flasher: for flashing the ESP8266 with tasmota firmware  
[Link](https://github.com/marcelstoer/nodemcu-pyflasher/releases/tag/v5.0.0)  
Tasmota firmware: firmware bootloader for esp8266  
*Note: download the tasmota.bin file*  
[Link](https://ota.tasmota.com/tasmota/release/)  
