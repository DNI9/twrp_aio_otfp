`git clone https://github.com/DNI9/twrp_aio_otfp.git -b twrp device/lenovo/aio_otfp`

`export ALLOW_MISSING_DEPENDENCIES=true; . build/envsetup.sh; lunch omni_aio_otfp-eng; mka recoveryimage`

`for busybox error : export TW_USE_TOOLBOX=true`

TWRP~SHRP device tree for Lenovo K3 Note
==============

This branch is for building TWRP 3.x.

### Working:
  - Touch
  - Display
  - Backup & Restore
  - Mount MTP storage
  - Mount USB-OTG
  - Wipe data (excl. internal storage)
  - NVRAM partition backup/restore
  - Logo partition backup/restore
  - Backup encryption
  - ADB sideload
  - Reboot to system, bootloader, recovery
  - Power Off
  - Time Zone selection
  - Vibration
  - Brightness

### Other resource:
  - Kernel: 3.10.105 (PixlernBlitz)

### Credits :
  - Aryan Kedare
  - Rohan Taneja
  - Adam Belamri
  - Sandeep Sethi
  - My Brain
