# Kernel Source Provenance

Base: SM-F711B_15_Opensource.zip -> Kernel.tar.gz (opensource.samsung.com, Android 15, SM-F711B)
Delta applied on top: F711BXXSIJZE5_kernel.tar.gz (opensource.samsung.com,
"SM-F711B_15_Opensource_F711BXXSIJZE5_..." release), per its included instructions:
  1. Download and unzip the kernel source of F711BXXUCJYD9 (base).
  2. Unzip and update the kernel source of F711BXXSIJZE5 (this delta).

This tree = base + delta, matching the F711BXXSIJZE5 baseband/build used in the
UN1CA b2q (Galaxy Z Flip3 5G) unofficial ROM build.

Device tree/defconfig confirmed present: arch/arm64/configs/vendor/b2q_eur_openx_defconfig
