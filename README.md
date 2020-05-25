![GitHub All Releases](https://img.shields.io/github/downloads/maccoylton/esp-homekit-motion-sensor/total)
![GitHub Releases](https://img.shields.io/github/downloads/maccoylton/esp-homekit-motion-sensor/latest/total)

# esp-homekit-motion-sensor

A HomeKit firmware for an infrared motion sensor HC-SR501- this uses an over the air (OTA) mechanism create by @HomeACcessoryKid 

Forked from :  maccoylton/esp-homekit-motion-sensor 

NOTE: This utilizes  pfalcon/esp-open-sdk and SuperHouse/esp-open-rtos  to compile.  

Please follow : pfalcon/esp-open-sdk#342 Esp. note the part of the issue by phibo23 commented on Mar 14, 2019 near the bottom. I needed to do all of that to get it built (on a case-sensitive volume)

Also this will need all three pieces to be checked out as --recursive.

To compile you will also need this set : export SDK_PATH=/Volumes/case-sensitive/esp-open-rtos
(that's how the path looks for me, on the case sensitive volume I created on my Mac -- running Catalina )

Also, either change permissions on the case-sensitive.dmg file or use sudo hdiutil attach -readwrite case-sensitive.dmg
