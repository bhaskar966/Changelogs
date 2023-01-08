|| 7/1/23 ||

**[Click to see changelog](https://raw.githubusercontent.com/bhaskar966/OTA/main/DerpFest/changelog_sweet.txt)**

**Notes**

- clean flash recommended
- Fixed low quality photo issue
- Fixed Deep Sleep
- Jan SP
- No MIUI cam
- Aperture working fine
- OTA enabled, from now you get updates via OTA.
- There is a bug which shows update availble even if you are in latest version; just ignore that it would not download automatically.
- to get updates via OTA you need to chnage private DNS to dns.google or any which can load raw.githubcontent as this is blocked in Jio. Same applies if you cant see the chnagelog linked here.
- source fixed that quick pull down issue - check the setting in gestures settings.

Credits -

Mr. Fox vt,dt

itsshashanksp for kt

@ItzBongBoy for testing


|| 2/1/23 ||

***Source Side***
- Switch to jemalloc memory allocator
- debuggerd: Disable scudo usage
- libcameraservice: Add support for miui camera mode
- DNM Revert "Camera: Add support for readout timestamp"
- Camera: Miscellaneous fixes in QDataCallback and binder death scenarios.
  - CameraService: Fix deadlock in binder death cleanup
  - Camera: CameraHardwareInterface: Releasing mHIDLMemoryMapLock in QdataCallback
  - Camera:CameraService: Added lock on mHIDLMemPoolId in QDataCallback
- --

***Device Side***
- Initial Build
- Added Leica(MIUI) Camera
- Added OnePlus Dolby Atoms
- Set preferred refresh rate on keyguard to 60
- Import OzoProcessing from MIUI Alioth 13.0.7.0 EU
- Remove audio postprocess effects and add OZO Processing
- Add Missing Media Codecs
- --


Notes -
- Added MIUI cam.
- Sleepy Kernel by default.
- OrangeFox recovery Recommended.

Credits -

Mr. Fox vt,dt and MIUI Cam

itsshashanksp for kt

@JYR_RC fox giving fixes to implement MIUI cam.

@Dolgoson for testing
