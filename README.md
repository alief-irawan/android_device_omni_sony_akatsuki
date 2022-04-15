TWRP Device Tree for Xperia XZ3 (akatsuki)
====
## Get source
TWRP repository
```sh
repo init --depth=1 -u https://github.com/minimal-manifest-twrp/platform_manifest_twrp_omni.git -b twrp-10.0
repo sync -j2
```
device tree for Xperia XZ3 (Akatsuki)
```sh
git clone https://github.com/alief-irawan/device_omni_sony_akatsuki.git -b android-10.0 device/sony/akatsuki
```

## Build
```sh
. build/envsetup.sh
lunch omni_akatsuki-eng
mka adbd bootimage
```
