# RaspberryPi Tor Router
---
Tor Router based on RaspberryPi (Raspbian).  

Needed :  
- RaspberryPi with Raspbian
- Internet Connection
- USB Ethernet Dongle (for eth1 interface)

Structure :
- Main Ethernet Port (eth0) will give Internet connection to the RaspberryPi
- USB Ethernet Dongle will give your computer/switch or whatever TOR Internet Access

Installation :  
1. Git Clone this repo.
2. Enter the repo directory
3. Run `sudo sh tordeploy.sh` (Yes, __sudo__ is needed, if it's runned __without sudo will give errors__)
