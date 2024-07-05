# Android device tree for samsung SM-A5560 (a55x)
# Clone
    git clone https://github.com/MrFluffyOven/android_device_samsung_a55x.git -b twrp-12.1 device/samsung/a55x

To build:
```bash
export ALLOW_MISSING_DEPENDENCIES=true
. build/envsetup.sh
lunch twrp_a55x-eng
mka vendorbootimage
```
# Build
Clone the following repository and use the git actions builder written by cd-Crypton
[Link](https://github.com/TheNoobDevs/samsung_a55x_vendorbootimage-builder)

## Credits
- [cd-Crypton](https://github.com/cd-Crypton)
