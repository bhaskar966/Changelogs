|| 28/6/23 ||

***Device Side***

sweet: Checkout audio configs from MIUI 13

sweet: gps: Update to LA.UM.9.1.r1-12900-SMxxx0.0

sweet: Reduce the list of pinned acdb files

sweet: Override doze mode support

sweet: sepolicy: Label Spi IR node

sweet: overlay: Limit screen recorder to 90fps

sweet: overlay: SystemUI: increase front camera ring size

sweet: sepolicy: Label wakeup node

sweet: overlay: Disable battery light settings

sweet: Update blobs from sweet V14.0.3.0.TKFEUXM

sweet: Drop Lineage livedisplay

sweet: Convert xiaomi_framework_compatibility_matrix.xml into device_framework_matrix.xml

sweet: overlay: Update vibration patterns

sweet: Update Audio HIDL to 7.1

sweet: Drop support for F2FS compressions and garbage collector

sweet: Build missing bluetooth libs

sweet: Remove hotword permission and whitelist xml files

sweet: overlay-voltage: Reduce no. of max visible notification icons

sweet: Disable continuous transaction tracing on all build types

Revert "sm6150-common: Enable backpressure propagation in SF"

sweet: Move BT profiles props to vendor

sweet: Clean up sepolicy

sweet : sepolicy: Label certain Xiaomi specific property labels

sweet : sepolicy: Allow rild to read default_prop

sweet: sepolicy: fix wifi denial

sweet: sepolicy: add ro.hardware.chipname prop

sweet: vintf: Declare hals

sweet: Remove duplicate mixer paths

sweet: overlay: Adjust status bar paddings

sweet: Don't latch unsignal buffers

sweet: Disable Skia tracing by default

sweet: Remove max ZRAM compression streams setting

sweet: sepolicy: Remove no longer existing properties

sweet: Fix IMS symlink as per dynamic partitions

Revert "sm6150-common: Force restorecon for /mnt/vendor/persist"

sweet: Set no_sehash_xattr on /mnt/vendor/persist

sweet: Add hotword enrollment blobs from vayu

sweet: Add missing DRM dependencies

sweet : Enable Camera Vendor Tags for Xiaomi devices

sweet : Inharit Pixel Launcher Extended(PLE)

sweet : nuke Priv-app permissions

***Source Side***

- SystemUI: Adjust qqs top margin dimension 
- DisplayModeDirector: Allow to enforce user selected resolution 
- Import support of custom screen resolution setting for supported devices
- Import latest Crowdin Translations
- overlay: Enable Quick Launch V2 in Pixel Launcher
- Revert "SystemUI: Adjust qqs top margin dimension
- hardware/interfaces: Update HIDL overrideFormat from HAL 
- frameworks/av: Camera: Import Xiaomi BufferProducerDetachListener changes 
- frameworks/native:
* Native: Camera: Import Release Slot Xiaomi Changes
* Native: ProducerListener: Import ON_BUFFER_DETACHED Changes
- Frameworks/base: Camera2: Notify fps as Session Based Parameter
- Frameworks/av changes:
* Camera: Flush Improvements - Result drain optimization
* libstagefright: Support YVU420SemiPlanar camera format
* camera: Don't segfault if we get a NULL parameter
* camera2 vndk: Improve error handling
* camera: Workaround for GCC-compiled HAL3 drivers
- frameworks_av: CAMX: CHI: Added support for handling jpeg debug data.
- Frameworks/base:
* camera: Allow selected camera apps to skip unconfigure
* Camera: Don't throw exceptions when value pairs have spaces in them
* Allow sending vendor- or device-specific commands to the camera HAL.
* Fix Photosphere/Camera FCs 
* CameraManager: Fixup exposing aux camera to apps 
* Camera: Ignore torch status update for aux or compsite camera
* Guard in short-circuit evaluations for stringSplit methods.
* Camera: Extend face detection
* Camera: Clearing exception for Extended Face
* camera: Support exposing aux camera to apps
* Add config overlay to force enable multi resolution for camera
* CameraManager: HAX for depth sensor on Miui Camera [1/2]
* Camera: Don't crash when trying to disable shutter sound
* Camera: Fix size list parceling
* CameraManager: Handle NPE with ActivityThread.currentOpPackageName()
* Camera: Avoid possible NPE after extension session configuration
* Camera: Prevent crash with prebuilt camera metadata
- Frameworks/av:
* HACK: libcameraservice: Make system cameras available to all camera apps 
* Camera: Add support for manual 3A.
* libstagefright: Allow HFR-60 in HAL-3 recording 
* libcameraservice: HAX for depth sensor on Miui Camera [2/2]
frameworks/base: Import Xiaomi Image Tags defenitions
frameworks/av: Import Xiaomi Image Tags defenitions
- Big rework of PixelPropsUtils:
* Drop previous GameProps
* Imported updated GameProps with better code to apply props for games and apps
* Spoof only walleye fingerprint for Play Store for CTS, show correct device itself for apps
* Switch some services to Pixel 7 Pro
* Hide Call of Duty, Black Desert, Fifa, Asphalt 9 to ROG6
* Allow spoofing device model for Netflix
* Add Gameprops for Battlegrounds Mobile India (BGMI) (Smooth-Extreme to HDR-Extreme)
Changes available in Github
 (https://github.com/VoidUI-Tiramisu/frameworks_base/commits/aosp-13)- Update frameworks crowdin translations to latest version
- Settings: Enable copying content for IMEI2 
- PixelPropsUtils: Switch Honor of Kings hide to Xiaomi 13 Pro (China) (2210132C)
- Resync with latest PE changes (QPR2)
* Settings: Properly set Wi-Fi Privacy spinner initial state
* Settings | Frameworks | Devicesettings - Automatic translation import 
* vendor/aosp: Fix now playing configs
* Frameworks/base:
Revert "SystemUI: Only apply tuning changes when the fragment is attached"
SystemUI: Avoid using null Context in onTuningChanged() 
fixup! Configurable 0, 90, 180 and 270 degree rotation 
Request correct rendering type for EGL config
SystemUI: React to PrivacyConfig changes properly
- Minor fixes and reworks
- Frameworks/base:
* Camera: Avoid holding locks during advanced extension initialization 
* Camera: Always release the extension session after configuration
* Camera: Release advanced extension references 
* Camera: Quit extension handler thread during release
* Fix the memory leak during high speed recording
- Frameworks/av:
* libcameraservice: Import Xiaomi Exif Camera Modifications
* libcameraservice: Import Xiaomi DistortionMapper Modifications

   And many more...


*Credits - *

Mr. Fox vt,dt

vantom for kt

[Team Files](https://telegram.me/modulesrepo) for PLE.

@JYR_RC for Lecia cam.

@virtualord for testing

- --

|| 31/3/23 ||

***Device Side***

sweet : overlay: Increase status bar top padding

sweet: Build missing omx libs

sweet: Add newly added blobs to public.libraries.txt

sweet: Add some missing blobs

sweet: Remove discard command tuning

sweet: overlay: Disable NearbyMessagingService

sweet: overlay: Disable DiscoveryService

sweet: Set correct manufacturer

sweet: overlay: Disable subtle tick vibration when revealing shelf

sweet: Update Adreno to LA.UM.9.14.r1-21000-LAHAINA.QSSI13.0

sweet: Update DPM, IMS, and RIL system blobs

sweet: Import missing blobs

And many more underwood changes


***Source Side***

March - 

GameSpace

* Own Updater & OTA updates

* Included ART fixes for best device CPU support & Kryo585 optimizations

* Per-app volume control

* Full Screen Navigation mode

* Full working AOD & Smartspace

* GameProps with hides for popular games

* Custom QS Tiles

* Burn-in protection for status/navbar

* Latest Crowdin tranlsations for all system customizations

* Ignore window secure flags (Can make screenshots in any app)

April - 

* Added UMO turbulence noise and surface ripple for Media Player

* Added support of scheduling always on display 
* Added Optimized Monet Engine customizations support:
- Theme styles selection
- Color Source selection
- Accent Colors selection
- Accent Background Colors selection
- Luminance and Chroma values tunings and ability to apply them for Background Tint
* Added support of Black Theme
[Warning! It requires to do not disable "Gesture Indicator" option to work correctly
P.s Works fine with Immersive navigation option]
* Fix issues with GameSpace Screen Recording option
* Includes PE Plus April patch fixes and Gapps update

May - 

* Update to May Security patch & Gapps
* Allow disabling refresh rate lowering in battery saver
* Various Performance optimizations
* Reduce screenshot dismiss delay to 3 seconds
* Add toggle for 3-button navbar inversion
* Update Aperture to latest available version

* Reworked and improved GameSpace to latest available version & fix visual bugs
* Update Aperture to latest available version
* Add support of showing Data usage in QS Footer
* Fix Updater to show the correct percentage during package installation 
* Additional improvements for Cameras support systemwide
* Add camera & flashlight buttons in lockscreen by default
* Update Qualcomm interfaces to latest CLO tag, import CRC buffer calculation backend
* Update Qualcomm display repos to latest CLO tag
* Enable Java R8 optimizations for system_server and SystemUI
* Import latest Crowdin Translations systemwide

And many more changes...


*Credits - *

Mr. Fox vt,dt

vantom for kt

@nutelladev for help to fic Leica cam.

@JYR_RC for Lecia cam.

@Coolaslikeice for testing




|| 21/2/23 ||

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

sweet: VoidUi BringUp

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

sm6150-common : VoidUi BringUp

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

***Source Changelog :-***


• 07 Feb:
- Switch to our fork of 
vendor/qcomlopensource/
commonsys/display & commonsys-intf/display
- Update commonsys/display & commonsys-intf/display to TAG: LA.QSSI.13.0.r1-09000-qssi.0
- Cleanup of changes in hardware/qcom-caf/sm8250/display
- If display drivers can not be compiled due to updated tag, but reserved_size missing: Use following fix in BoardConfig
- Updated Aperture to latest available version
- Updated GMS (GAPPS) to latest version on which switched PE.
(Gapps from Pixel 5, having no included tensor add-ons so works feeled better on Qcom and non-tensor devices. Also included apps are less and size of rom is less after this change. Clean installation is preferable, but dirty checked also worked fine)

08 Feb:
- Update Aperture to latest available version:
* Aperture: Add DPP QR handling
* Aperture: Add Wi-Fi QR handling
* Aperture: Add ripple animation for QR CardView
* Aperture: Add support for Assistant actions 
* Additional code improvements ...

09 Feb: CTS integrity fix

12 Feb:
Short changelog:
* Show alarm icon in statusbar if alarm is set
* Update Smartspace
* Removal of some debuggings
* Enable additional Pixel features flags
* Fix compilation and Pixel launcher for Tablets
* Disable Safe Volume
* Add Pixel battery addons to Settings - Battery

13 Feb:
* Rework Updater changes, based on LOS-20 + crdroid impl on top + our adaptation
* Disable recovery_update flag by default
* Address sys.recovery_update sepolicy
* Resync with latest PE changes, and rework our changes on top
* GameSpace: Remove dim layer from the panel view

18 Feb: Android 13 Release 30 | Feb Patch

19 Feb:
- Clean rework of all features on top of latest PE changes
- Cleanup of previous changes
- Clean reimport of translations from crowdin
- In this update also fixed AOD Weather / Music info showing
- Update of Aperture to latest version
- Update devicesettings translations
- Cleanup of redundant changes for safetynet bypass
- Cleanup of features overlays

**Notes -**

- Don't use refresh rate profile, it's crashing.
- No MIUI cam.
- Aperture cam by default.
- Sleepy Kernel by default.
- OrangeFox recovery Recommended.

*Credits -*

Mr. Fox vt,dt

vantom for kt

@ItzBongBoy and @DA_R_T for testing

- --

|| 21/1/23 ||

***Device Side***
- added hardware/xiaomi from lineageos
- sweet : Move to common libhidl
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
- sm6150-common: Move to common libpiex shim
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

***Source Changelog***


Based on QPR1 Base | android-13.0.0_r23 | January Security Patch

Entire ROM moved cleanly to new QPR1 Release base
Based on latest Pixel Experience Plus
Also Added part of our custom features:


- Cutout force full screen 
- Custom QS Tiles: Data Switch | Auto Brightness | CPU Info | FPS Info
- GameProps
- GameSpace
- ReTicker
- Full Screen (Immersive) navigation without pill
- Screen Recorder Customizations
- Updated external_fastrpc to latest version
- kryo785 architecture support
- Various system side optimizations and fixes
- And more...


Notes -
- No MIUI cam.
- Aperture cam by default.
- Sleepy Kernel by default.
- OrangeFox recovery Recommended.

Credits -

Mr. Fox vt,dt

itsshashanksp for kt

@ItzBongBoy for testing


---
