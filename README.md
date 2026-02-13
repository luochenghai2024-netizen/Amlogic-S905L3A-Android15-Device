# Amlogic-S905L3A-Android15-Device
Android 15 Treble Device Tree for Amlogic S905L3A TV Box | 4.9 Kernel | AIDL Vendor

# Amlogic S905L3A - Android 15 Treble

Device support files for Amlogic S905L3A TV Box with Android 15 Treble and AIDL vendor.

## Device Specifications
- Chipset: Amlogic S905L3A, boosted from 1.8GHz to 1.92GHz
- Kernel: Linux 4.9 (including backported features)
- Architecture: ARM
- Storage: 8GB eMMC
- Super partition size: 2GB
- Cache partition: Reduced from 1GB to 16MB via DTS modification
- By compressing the cache partition by modifying the device tree file, the available space in the data partition increased to approximately 4.4 GB (on an 8GB eMMC device).
## Features
- Standard Project Treble support
- Display, Audio, Bluetooth working
- Video decoding and GPU 3D working
- Optimized for 8GB small-storage devices
- Stable for daily usage

## Important Notes
- 4.9 kernel can continue to run new Android versions due to Treble + AIDL.
- Upgrading to kernel 5.x or higher is **NOT recommended**, as it will break GPU/3D functions.

## Credits
*Amlogic*

*[ZNDS](https://www.znds.com/tv-1257378-1-1.html) - @Greatson*

*[CSDN](https://blog.csdn.net/FlyShooter01/article/details/145212229). - @Sicha思咖*

*Treble Developers*

*[LineageOS](https://download.lineageos.org/devices/radxa0_tab/builds). - @bgcngm @npjohnson @stricted*
