# UniFi Pi
UniFi Network Server as ready to use image with Webmin WebGUI for Appliance-Management for Raspberry Pi, Single Board Computers and HyperVisors.

## Releases:
### General Information:
The punblished releases are only snapshots of my current used UniFi Network Server devices. So don't punish me if something doesn't work for you.
You can find the current snapshots in the releases tab of this repo: https://github.com/hifishch/unifi-pi/releases

## Default Settings:
* IP: DHCP
* Fallback IP: 192.168.1.254/24 (OVF VMs don't support Fallback-IPs)
* Hostname: unifi
* User: ubnt
* Passwort: ubnt

## Admin Portals:
* Webmin: https://unifi:10000
* Unifi Network Server: https://unifi:8443 

## Notes:
* It’s recommended to change the default password for the user “ubnt” after the initial setup. This can be done via SSH or Webmin.
* The UniFi Network Server can be updated via Webmin or via SSH unsing the UniFi Easy Update Script by Glenn R. (https://community.ui.com/questions/UniFi-Installation-Scripts-or-UniFi-Easy-Update-Script-or-UniFi-Lets-Encrypt-or-UniFi-Easy-Encrypt-/ccbc7530-dd61-40a7-82ec-22b17f027776)

## Special Thanks:
Special thanks to Glenn R. (https://glennr.nl) for publishing his helpful install and upgrade scripts for the UniFi Network Server
