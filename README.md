# Unifi Pi
Unifi Network Server as ready to use image with Webmin WebGUI for Appliance-Management for Raspberry Pi and other Single Board Computers

### General Information:
The punblished Images are only snapshots of my current used Unifi Network Server devices. So don't punish me if something doesn't work for you.

## Default Settings:
* IP: DHCP (Fallback IP: 192.168.1.254/24)
* Hostname: unifi
* User: ubnt
* Passwort: ubnt

## Admin Portals:
* Webmin: https://unifi:10000
* Unifi Network Server: https://unifi:8443 

## Notes:
* It’s recommended to change the default password for the user “ubnt” after the initial setup. This can be done via SSH or Webmin.
* The Unifi Controller can be updated via Webmin or via SSH unsing the UniFi Easy Update Script by Glenn R. (https://community.ui.com/questions/UniFi-Installation-Scripts-or-UniFi-Easy-Update-Script-or-UniFi-Lets-Encrypt-or-UniFi-Easy-Encrypt-/ccbc7530-dd61-40a7-82ec-22b17f027776)

## Used Software and Scripts:
Used Software and Scripts:
### Raspberry Pi OS Lite
* Release Date: July 4th 2024
* Kernel version: 6.6
* Debian version: 12 (bookworm)
* Reference: https://www.raspberrypi.com/software/operating-systems/
### Webmin
* Version: 2.202
* Reference: https://webmin.com/download/
### Unifi Network Server
* Version: 8.4.62-26656-1
* Reference: https://ui.com/download
### MongoDB
* Version: 7.0.14 [Compiled by AmazedMender16 (Glenn R.)]
* Reference: https://www.mongodb.com/try/download/community-edition/releases 

## Special Thanks:
Special thanks to Glenn R. (https://glennr.nl) for publishing his helpful install and upgrade scripts for the Unifi Network Server
