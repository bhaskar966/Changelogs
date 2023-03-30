|| 30/3/23 ||

Switch to new Tree.

|| 25/2/23 ||

***Device Changelog :-***

sweet: Update the s5kgw3 camera libraries from MIUI V13.0.9.0.SKFINXM

sweet: Drop xiaomi touchfeature hal

sweet: overlay: Disable battery light settings 

sweet: overlay: cancel FP operation if not idle

sweet: Update blobs from sweet V13.0.17.0.SKFEUXM 

sweet: overlay: Migrate "rounded_corner_content_padding"

sweet: overlay: Increase status_bar_padding_top

sweet: sepolicy: Allow hal_displayfeature_xiaomi_default to write

sweet: Switch to vantom and playground 16 clang

sweet: overlay: Adjust status bar round corner

sweet: Bliss ROM Bringup

sweet : Move to common libhidl

Dolby: Remove duplicate in manifest

sweet: devicesettings: Drop 90 Hz option in per-app refresh rate 

sweet: devicesettings: Introduce haptic feedback level adjustment

sweet: devicesettings: Adjust Haptic feedback title and summary

sweet: devicesettings: Add icon for Haptic feedback SeekBar

sweet: devicesettings: Add summary for custom haptic feedback

sweet: devicesettings: Update Haptic feedback layout

sweet: devicesettings: Adapt Haptic Settings for A12 Style 

sweet: devicesettings: change haptic level node for sweet

sm6150-common: wifi: tune bmps listening interval

sm6150-common: gps: Update to LA.UM.9.1.r1-13000-SMxxx0.QSSI13.0

sm6150-common: dolby: Add dolby mediacodecs support

sm6150-common: sepolicy: Allow system suspend to read sysfs dir 

sm6150-common: sepolicy: add permission to request health/sensor data 

sm6150-common: Remove references to a2dp module

sm6150-common: Remove AUDIO_FEATURE_ENABLED_PROXY_DEVICE

sm6150-common: Drop custom APM flag along with no-op audio flags

sm6150-common: prop: Compact cached app heaps in the background 

sm6150-common: Pin Dirac blobs

sm6150-common: manifest: Add missing vintf entries

sm6150-common: Drop component overrides

sm6150-common: Deduplicate handheld_core_hardware.xml copy rule

sm6150-common: Unpin updatable-media from memory 

sm6150-common: Update telephony package list to LA.QSSI.12.0.r1-05600-qssi.0

sm6150-common: Move ueventd.qcom.rc to /vendor/etc. 

sm6150-common: hwc: Disable SF composition prediction model.

sm6150-common: media: Add swap width and height feature

sm6150-common: media: Fix VTS issue. 

sm6150-common: sepolicy: Address some denials

sm6150-common : Bliss ROM Bringup

sm6150-common : Switch to Vantom Kernel and playground clang

sm6150-common: Move to common libpiex shim

sm6150-common: Set PRODUCT_SET_DEBUGFS_RESTRICTIONS 

sm6150-common: Add system prefix to proprietary libraries in /system

sm6150-common: Automatically add apk/jar/vintf fragments to PRODUCT_PACKAGES

sm6150-common: Move qti_whitelist.xml to /system_ext

sm6150-common: Build DRM 1.4 to vendor

sm6150-common: Enable AIDL DRM HALs 

sm6150-common: properties: Remove unused persist.bluetooth.a2dp_offload.cap property

sm6150-common: Enable backpressure propagation in SF

sm6150-common: Disable remote Keygaurd animation 

sm6150-common: make the UI smoother

sm6150-common: props: RIL edits for battery life.

sm6150-common : nuke duplicates

*vendor
sweet: Update the s5kgw3 camera libraries from MIUI V13.0.9.0.SKFINXM 

sweet: Drop xiaomi touchfeature hal

sm6150-common: Update blobs from sweet V13.0.17.0.SKFEUXM 

sweet: Update blobs from sweet V13.0.17.0.SKFEUXM

sm6150-common: Import missing dirac blobs



Notes -
- No MIUI cam.
- Vantom Kernel by default.
- Use this [GCam](https://www.apkmirror.com/apk/bsg/gcam-bsgs-google-camera-port-org-codeaurora-snapcam/camera-27-8-1-101-345618084-release/camera-8-1-101-345618084-3-android-apk-download/) for use all lenses.
- Recommended Gapps is NikGapps for Vanilla Build.
- OrangeFox recovery Recommended.

- --

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
