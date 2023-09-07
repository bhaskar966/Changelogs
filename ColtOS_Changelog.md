|| 7/9/23 ||

**Device Changelog --**
- Initial Official relase 
- sweet: set TARGET_2ND_ARCH_VARIANT to armv8-2a
- sweet: Add vendorsetup.sh
- sweet: switch to r487747c clang

**Notes --**

- Clean flash is recommended as this is the initial Official build
- Use BitGapps core for vanilla
- Use OrangeFox Recovery, Recommended version is 11.1_3
- Aperture cam added with all lens support
- Sleepy kernel by default


**Credits**

@Mr. Fox vt,dt

@itsshashanksp for kt

- --

**Device Changelog**

- sweet: change TARGET_KERNEL_CONFIG to sweet_deconfig
- sweet: overlay: Add aperture camera to AuxPackageAllowLis
- sweet: overlay-colt: Configure additional camera framerates
- sweet: overlay-colt: Configure aux camera for Aperture
- sweet: set TARGET_2ND_ARCH_VARIANT to armv8-a
- sweet : ColtOS Bringup
- sweet : Nuke VoltageOS strings and configs
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
- Use OrangeFox Recovery, Recommended version is 11.1_3
- Aperture cam added with all lens support


**Credits**

@Mr. Fox vt,dt

Vantom for kt

@Coolaslikeice for testing
