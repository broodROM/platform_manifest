broodROM Manifest
=============================

broodROM is a custom ROM based on AOSP 4.4.2 KitKat (https://github.com/AOSP-S4-KK) which aims for very high performance, a good battery life and great usability.


> Current Phase: Development Started





Download:
----------
* mkdir ~/broodROM
* cd ~/broodROM
* repo init -u git://github.com/broodROM/platform_manifest -b kk-4.4
* repo sync





Building:
----------
* . build/envsetup.sh
* lunch
* make otapackage
