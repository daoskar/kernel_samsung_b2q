# kernel_samsung_b2q

Kernel source for the Samsung Galaxy Z Flip3 5G (SM-F711B, codename `b2q`),
published to satisfy GPLv2 source-availability requirements for the
[UN1CA 3.2.0 unofficial ROM port](https://github.com/salvogiangri/UN1CA) for this device.

**This is not a custom/modified kernel.** It is the stock kernel source as
released by Samsung, matching the firmware used to build the ROM
(`F711BXXSIJZE5`). See `SOURCE_PROVENANCE.md` for exactly how this tree was
assembled from Samsung's Open Source releases.

- Device: Galaxy Z Flip3 5G (SM-F711B)
- Platform: Qualcomm Snapdragon 888 (SM8350 / lahaina)
- Defconfig: `arch/arm64/configs/vendor/b2q_eur_openx_defconfig`
- Firmware/build: F711BXXSIJZE5
- License: GPL-2.0 (see `LICENSE` / `COPYING`)

## Build

See `README_Kernel.txt` for Samsung's original build instructions (toolchain,
defconfig, output paths).
