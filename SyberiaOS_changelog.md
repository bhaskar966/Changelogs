**Device Changelog**

- sweet: Nuke duplicate sepocily rules
- sweet: overlay: Add aperture camera to AuxPackageAllowLis
- sweet: overlay-syberia: Configure additional camera framerates
- sweet: overlay-syberia: Configure aux camera for Aperture
- sweet: Project Syberia bringup
- sweet : Nuke VoltageOS configs
- sweet: ueventd: Remove all permissions from /sys/devices/soc0/serial_number
- sweet: Kang libspl.so from LA.UM.9.1.r1-12900-SMxxx0.0
- sweet: Switch to AutoSingleLayer Android 13 Setting
- sweet: Disable SurfaceFlinger EGL image tracking
- sweet: rootdir: Enable suspend to RAM
- sweet: rootdir: Use s2idle instead of deep
- sweet: Import missing audio & sensor libraries
- sweet: sepolicy: Allow recovery to access /sys/fs/pstore/*
- sweet: overlay: adjust rounded corner radius top and bottom padding
- sweet: sepolicy: allow system app access zram0
- sweet: Move power-mode.cpp to configs/power
- Revert "sweet: overlay: SystemUI: increase front camera ring size"
- sweet: rootdir: Remove vbmeta_system from fstab
- sweet: Update hotword blobs from V14.0.2.0.TKFMIXM
- sweet: sepolicy: Allow SF to read firmware
- sweet: Remove non-existent modules
- sweet: Disable backpressure prop
- sweet: Switch BtAudio to HIDL
- sweet: Disable zram writeback
- sweet: props: Kang sf props from pixel(raven)
- sweet: configs: audio: Fix "Earpiece" audio output
- sweet: overlay: Increase start and end padding of status bar
- sweet: Update GPS blobs from hanoip S2RIS32.32-20-7-7
- sweet: configs: update GPS configs from hanoip S2RIS32.32-20-7-7
- Revert "sweet: overlay-voltage: Reduce no. of max visible notification icons"
- sweet: overlay: Fix padding
- sweet : Nuke VoltageOS configs

**Notes**

- Clean flash mandatory as this is the initial build
- Use BitGapps core in vanilla
- Use this [GCam](https://www.apkmirror.com/apk/bsg/gcam-bsgs-google-camera-port-org-codeaurora-snapcam/camera-27-8-1-101-345618084-release/camera-8-1-101-345618084-3-android-apk-download/) for use all lenses. If you any other then let me know in the telegram group.
- Use OrangeFox Recovery, Recommended version is 11.1_3
- Aperture cam added with all lens support
- Issue: Owner(User) Section in settings is crashing, seems like a source issue. So, don't report that. ~ It's minior issue, this wouldn't affect your daily uses.


**Credits**

@Mr. Fox vt,dt

Vantom for kt

@Coolaslikeice for testing
