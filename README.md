1. Switch selinux from enforcing to permissive. Recommended app- https://forum.xda-developers.com/android/apps-games/app-selinux-switch-t3656502 
2. Download OTA in updater. 
3. Install. DONT TAP REBOOT YET, because updater changed slot. 
4. Go to magisk, install module named "TWRP A/B Repartition". It's needed to keep TWRP alive. 
5. In main magisk menu, press install, then "Install to inactive slot after OTA". It's needed to flash magisk to inactive slot, because updater changed slot, where magisk doesn't exist. 
6. Reboot to recovery. 
7. Flash Gapps (same version when installing 1st time, i mean nano/pico etc.), magisk, Camera2Api Enabler and kernel if want.
8. Reboot to system. 
9. Switch from SELimux status from permissive to enforcing.
10. Proof.

If you want to keep magisk 18.1 in step 5, paste this to custom URL in Magisk>settings>channel
https://raw.githubusercontent.com/pawelik001/magisk_files/master/stable.json
