Here you have a simple guide, how to properly udpate a SuperiorOS using OTA (Updater app). 

If you want to keep Magisk 18.1 in step 5, paste this to custom URL in Magisk>settings>channel
https://raw.githubusercontent.com/pawelik001/magisk_files/master/stable.json

1. Switch selinux from enforcing to permissive. Recommended app- https://forum.xda-developers.com/android/apps-games/app-selinux-switch-t3656502 
2. Download OTA in updater. 
3. Install. DONT TAP REBOOT YET, because updater has changed slot. 
4. Go to Magisk, install module named "TWRP A/B Repartition". It's needed to keep TWRP alive. 
5. In main menu in Magisk, press "Install", then "Install to inactive slot after OTA". It's needed to flash magisk to inactive slot, because updater changed slot, where magisk doesn't exist. 
6. Reboot to recovery. 
7. Flash Gapps*, Magisk, and kernel if want.
8. Reboot to system. 
9. Switch from SELimux status from permissive to enforcing.
10. Take a taste of new update! :)

* flash same Gapps version when doing clean flash, so when during clean flash you've flashed gapps named: open_gapps-arm64-9.0-nano-20190813.zip, install the new version like open_gapps-arm64-9.0-nano-20190913.zip, not open_gapps-arm64-9.0-pico-20190913.zip, in overall dont change the variant. 

Credits:
@pawelik001 for this guide
@SuperiorOS for this AWESOME OS! <3
