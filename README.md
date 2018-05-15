# Irvines-Hardening-Project
Profiles, local customisations and tools for Firejail and AppArmor

## Overview
My current long term project is to experiment with building a high-security Os using [Arch Linux](https://www.archlinux.org). Apart from a commercial Vpn, disk encryption ... etc, the project basically consists of the following parts:
1. Use Firejail to sandbox **ALL** top level applications
1. My [apparmor enabled version](https://aur.archlinux.org/pkgbase/linux-hardened-apparmor/)  of the linux-hardened kernel
1. Write restrictive Apparmor profiles for sensitive low level daemons. eg `NetworkManager`, `openvpn`, `wpa-supplicant`, `gvfsd`, `udisks2`, `tumblerd`, .... etc
1. Write tools, particularly for Firejail, to help manage the enviroment.

I have split things up into three main sections
* [Firejail profiles and local customisations](https://github.com/Irvinehimself/Irvines-Hardening-Project/tree/master/FirejailProfiles)
* [Tools to manage Firejail profile](https://github.com/Irvinehimself/Irvines-Hardening-Project/tree/master/FjTools)
* [Apparmor profiles for daemons and low level utilites]()

For your convenience, each section has it's own readme with the important details


