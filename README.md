# Home Infrastructure
Just an Aussie Bloke trying to help other like minded IT nuts setup similar IT infrastructure in their own environments/homes/offices.

# Objectives
I want to start my Home Assistant journey by integrating my garage door into Home Assistant and open it through my phone.

# Infrastructure Design
I wanted to setup a raspberry pi and host most (if not all of) my applications within it via docker.  
The conditions of my containers must host the following applications,  
- mqtt broker
- Home Assistant

# Resources:  
## Hardware  
_All Australian Stores_  
Raspberry Pi 4 Model B 8GB: [PiAustralia](https://raspberry.piaustralia.com.au/products/raspberry-pi-starter-kit)  
Raspberry Pi 4 Case:  [Amazon](https://www.amazon.com.au/Smraza-Raspberry-Sinks-USB-C-Supply/dp/B07TTMQ4PH/ref=sr_1_103?crid=37W4RMCLMK2MJ&keywords=raspberry+pi+4+case&qid=1654862391&sprefix=raspberry+pi+4+cas%2Caps%2C247&sr=8-103)

#Garage Door  
ESP8266 NodeMCU V2 CP2102: [AliExpress](https://www.aliexpress.com/item/1005001636634198.html?spm=a2g0o.order_list.0.0.6d9818022rGaHn) 
5V Relay Switch: [Altronics](https://www.altronics.com.au/p/z6422-5v-2-channel-relay-control-module/) 
Magnetic Sensor: [Altronics](https://www.altronics.com.au/p/s5153-spdt-surface-mount-security-magnetic-reed-switch/)  

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
