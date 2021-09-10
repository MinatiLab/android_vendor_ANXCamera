# ANX Camera #
-------------------------------------------------------------------------------------------
### About ANX Camera ###

* Xiaomi MIUI Camera from MIUI 12.5
* Reported working fine on Android 10/11 AOSP ROMs.

## Building ANX Camera ##
* Clone this repository in `vendor/ANXCamera` in your ROM's Sourcecode & Build it by adding following command in your Makefile.
 
```
# ANX Camera
$(call inherit-product, vendor/ANXCamera/config.mk)
```

## Notes ##
* ANXCam works fine in Android 10 & 11 ROMs for Now.
* ANXCam Supports Non-Xiaomi Devices too.
