# Prebuilt Kernel & DLKM Images for Motorola Edge 40 (`lyriq`)

Prebuilt kernel, Device Tree Blob (`dtb`), vendor ramdisk kernel modules, and prebuilt DLKM partition images for **Motorola Edge 40 (`lyriq`)** (`lineage-22.1`).

## Contents

- **`kernel`**: Prebuilt GKI kernel image (`Linux 6.6.89` / Android 15 stock `V1TLS35.73-60-3-10`)
- **`dtb/mt6893.dtb`**: Compiled Device Tree Blob for `mt6893` / `MT6891Z`
- **`modules/*.ko`**: Vendor ramdisk & recovery loadable kernel modules (`modules.load`, `modules.load.recovery`)
- **`vendor_dlkm.img`** (`42 MB`): Prebuilt EROFS `vendor_dlkm` partition image containing MediaTek & Motorola hardware kernel modules
- **`system_dlkm.img`** (`12 MB`): Prebuilt EROFS `system_dlkm` partition image containing GKI system kernel modules
