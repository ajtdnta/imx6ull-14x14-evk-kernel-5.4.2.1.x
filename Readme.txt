by lancz
============
build for imx6ull(正点原子 ATK-DL6Y2C_V2.4)step:
1. make distclean
2. make imx_v7_defconfig
3. make -j16
4. cp arch/arm/boot/dts/imx6ull-14x14-atk-emmc.dtb mfgtool/Profiles/Linux/OS\ Firmware/files/boot/imx6ull-14x14-emmc-4.3-480x272-c.dtb
5. cp arch/arm/boot/zImage mfgtool/Profiles/Linux/OS\ Firmware/files/boot
