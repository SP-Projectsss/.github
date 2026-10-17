# SP-Projectsss

One device. Everything it takes to build for it.

**Xiaomi POCO F7** — `onyx` · Snapdragon 8s Gen 4 (`sun`) · LineageOS 23.2 / Android 16

![onyx](https://img.shields.io/badge/device-onyx-E60012?style=flat-square)
![base](https://img.shields.io/badge/base-LineageOS%2023.2-166BCC?style=flat-square)
![rootless](https://img.shields.io/badge/root-not%20needed-2EA043?style=flat-square)

This org holds the onyx-specific forks, blobs and patches that a stock LineageOS tree does not carry — so a fresh build needs tribal knowledge nowhere.

### What we ship

- **Leica camera** — patched MIUI camera app with the MiSyS HAL, watermarks and LUT filters rendering in every shot
- **Dolby Atmos** — sound effects alive, the audio HAL crash-loop repaired at the vendor-blob level
- **5G SA** status-bar badge on NR cells that report their data technology as unknown
- **Adreno GPU** driver imports paired with the matching Vulkan permission XMLs
- **Vibrator**, display and tuning features ported in from sibling Xiaomi trees

Nothing above needs Magisk or KernelSU. It is all in the ROM image.

**Maintainer:** [Sachinpawar86](https://github.com/Sachinpawar86)

### Credits
[**LineageOS:**](https://github.com/LineageOS) (`Base Trees`)

[**Fleur-Project:**](https://github.com/Fleur-Project) (`README Reference`)
