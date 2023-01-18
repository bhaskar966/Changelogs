|| 18/1/23 ||

***Device Side***
- added hardware/xiaomi from lineageos
- sweet: overlay: Set preferred refresh rate on keyguard to 60
- sweet: Update the s5kgw3 camera libraries from MIUI V13.0.9.0.SKFINXM
- sweet: Drop xiaomi touchfeature hal
- sweet: overlay: Disable battery light settings
- sm6150-common: Import OzoProcessing from MIUI Alioth 13.0.7.0 EU
- sm6150: Remove audio postprocess effects and add OZO Processing
- sm6150-common: Add Missing Media Codecs
- sm6150-common: Add battery saving props
- sm6150-common: props: Don't write binary XML files
- sm6150-common: props: Enable QCRIL radio power saving
- sm6150-common: Enable Seamless Transfer support
- sm6150-common: props: Fix Lockscreen unlock wakeup delay
- sm6150-common: props: Force triple frame buffers
- drop : Iorap
- sm6150-common: wifi: Switch gEnablePowerSaveOffload to 5
- Revert "sm6150-common: Import OzoProcessing from MIUI Alioth 13.0.7.0…
… EU"
- sm6150-common: drop android.hardware.tetheroffload.config manifest
- sm6150-common: Pin Google's SystemUI instead of AOSP's
- sm6150-common: Optimise dex flags
- sm6150-common: props: Add few props for performance
- sm6150-common: rootdir: Enable suspend to RAM
- sm6150-common: wifi: tune bmps listening interval
- sm6150-common: gps: Update to LA.UM.9.1.r1-13000-SMxxx0.QSSI13.0
- sm6150-common: dolby: Add dolby mediacodecs support
- sm6150-common: Import OzoProcessing from Miui Alioth 13.0.7.0 EU
- sm6150-common: Import missing blobs
- sweet: Update the s5kgw3 camera libraries from MIUI V13.0.9.0.SKFINXM
- sweet: Drop xiaomi touchfeature hal

Notes -
- No MIUI cam.
- Sleepy Kernel by default.
- Use this [GCam](https://sourceforge.net/projects/bhaskar-builds/files/GCaam/) for use all lenses.
- Recommended Gapps is NikGapps for Vanilla Build.
- OrangeFox recovery Recommended.

Credits -

Mr. Fox vt,dt

itsshashanksp for kt

@ItzBongBoy for testing


---

|| 16/12/22 ||

***Source Side***
- Switch to jemalloc memory allocator
- debuggerd: Disable scudo usage

***Device Side***
- Initial Build
- Added OnePlus Dolby Atoms
- Added Pixel Launcher MOD in Gapps Build(Thanks to #TeamFiles)
- Added libpiex shim back
- Added libhidl back


Notes -
- No MIUI cam.
- Sleepy Kernel by default.
- Use this [GCam](https://www.apkmirror.com/apk/bsg/gcam-bsgs-google-camera-port-org-codeaurora-snapcam/camera-27-8-1-101-345618084-release/camera-8-1-101-345618084-3-android-apk-download/) for use all lenses.
- Recommended Gapps is NikGapps for Vanilla Build.
- OrangeFox recovery Recommended.

Credits -

Mr. Fox vt,dt

itsshashanksp for kt

[TeamFiles](https://t.me/modulesrepo) For Pixel Launcher MOD
