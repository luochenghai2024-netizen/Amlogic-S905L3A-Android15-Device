# Amlogic-S905L3A-Android15-Device
Android 15 Treble Device Tree for Amlogic S905L3A TV Box | 4.9 Kernel | AIDL Vendor

# Amlogic S905L3A - Android 15 Treble

Device support files for Amlogic S905L3A TV Box with Android 15 Treble and AIDL vendor.

## Device Specifications
- Chipset: Amlogic S905L3A
- Kernel: Linux 4.9 (with backported features)
- Architecture: arm
- Storage: 8GB eMMC
- Super partition size: 2GB
- Cache partition: reduced from 1GB to 16MB via DTS modification

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
Amlogic, ZNDS: @Greatson (https://www.znds.com/tv-1257378-1-1.html)(https://www.znds.com/home.php?mod=space&uid=2855187),CSDN: @Sicha思咖 (https://blog.csdn.net/FlyShooter01?type=blog)(https://blog.csdn.net/FlyShooter01/article/details/145212229), Treble Developers
