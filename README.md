# Android device tree for samsung SM-A5560 (a55x)
# Clone
    git clone https://github.com/MrFluffyOven/android_device_samsung_a55x.git -b twrp-12.1 device/samsung/a55x
# Build
```bash
export ALLOW_MISSING_DEPENDENCIES=true
. build/envsetup.sh
lunch twrp_a55x-eng
mka vendorbootimage
```
# Source
[Link](https://github.com/TheNoobDevs/samsung_a55x_vendorbootimage-builder)

## Credits
- MrFluffyOven
