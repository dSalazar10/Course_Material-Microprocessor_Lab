# CMPE344
Microprocessor Lab
Primary Project Repo: https://github.com/tmartin293/Musical_Instrument_Classification

root@beaglebone:/opt/scripts/tools# ./version.sh
git:/opt/scripts/:[1aa73453b2c980b75e31e83dab7dd8b6696f10c7]
eeprom:[A335BNLT00C03818BBBK251D]
model:[TI_AM335x_BeagleBone_Black]
dogtag:[BeagleBoard.org Debian Image 2018-10-07]
bootloader:[microSD-(push-button)]:[/dev/mmcblk0]:[U-Boot 2018.09-00002-g0b54a51eee]:[location: dd MBR]
bootloader:[eMMC-(default)]:[/dev/mmcblk1]:[U-Boot 2018.09-00002-g0b54a51eee]:[location: dd MBR]
kernel:[4.14.71-ti-r80]
nodejs:[v6.14.4]
uboot_overlay_options:[enable_uboot_overlays=1]
uboot_overlay_options:[uboot_overlay_pru=/lib/firmware/AM335X-PRU-RPROC-4-14-TI-00A0.dtbo]
uboot_overlay_options:[enable_uboot_cape_universal=1]
pkg check: to individually upgrade run: [sudo apt install --only-upgrade <pkg>]
pkg:[bb-cape-overlays]:[4.4.20180928.0-0rcnee0~stretch+20180928]
pkg:[bb-wl18xx-firmware]:[1.20180517-0rcnee0~stretch+20180517]
pkg:[kmod]:[23-2rcnee1~stretch+20171005]
pkg:[librobotcontrol]:[1.0.3-git20181005.0-0rcnee0~stretch+20181005]
pkg:[firmware-ti-connectivity]:[20170823-1rcnee1~stretch+20180328]
groups:[debian : debian adm kmem dialout cdrom floppy audio dip video plugdev users systemd-journal i2c bluetooth netdev cloud9ide gpio pwm eqep admin spi tisdk weston-launch xenomai]
cmdline:[console=ttyO0,115200n8 bone_capemgr.uboot_capemgr_enabled=1 root=/dev/mmcblk0p1 ro rootfstype=ext4 rootwait coherent_pool=1M net.ifnames=0 quiet]
dmesg | grep pinctrl-single
[    1.119738] pinctrl-single 44e10800.pinmux: 142 pins at pa f9e10800 size 568
dmesg | grep gpio-of-helper
[    1.131778] gpio-of-helper ocp:cape-universal: ready
END
