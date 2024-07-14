README: Release 29 03 2019

This release supports the following projects:

Intel based FPGAs:
	socfpga_arria10_socdk_adrv9009
	socfpga_arria10_socdk_adrv9371
	socfpga_arria10_socdk_daq2
	socfpga_cyclone5_sockit_arradio

Xilinx based FPGAs:
	zynq-adrv9361-z7035-bob-cmos
	zynq-adrv9361-z7035-bob
	zynq-adrv9361-z7035-box
	zynq-adrv9361-z7035-fmc
	zynq-adrv9364-z7020-bob-cmos
	zynq-adrv9364-z7020-bob
	zynq-adrv9364-z7020-box
	zynq-zc702-adv7511-ad9361-fmcomms2-3
	zynq-zc702-adv7511-ad9361-fmcomms5
	zynq-zc702-adv7511-ad9364-fmcomms4
	zynq-zc702-adv7511
	zynq-zc706-adv7511-ad6676-fmc
	zynq-zc706-adv7511-ad9265-fmc-125ebz
	zynq-zc706-adv7511-ad9361-fmcomms2-3
	zynq-zc706-adv7511-ad9361-fmcomms5
	zynq-zc706-adv7511-ad9361-fmcomms5-ext-lo-adf5355
	zynq-zc706-adv7511-ad9364-fmcomms4
	zynq-zc706-adv7511-ad9434-fmc-500ebz
	zynq-zc706-adv7511-ad9625-fmcadc2
	zynq-zc706-adv7511-ad9625-fmcadc3
	zynq-zc706-adv7511-ad9739a-fmc
	zynq-zc706-adv7511-adrv9371
	zynq-zc706-adv7511
	zynq-zc706-adv7511-fmcadc4
	zynq-zc706-adv7511-fmcdaq2
	zynq-zc706-adv7511-fmcdaq3-revC
	zynq-zc706-adv7511-fmcjesdadc1
	zynq-zc706-adv7511-fmcomms11
	zynq-zed-adv7511-ad9361-fmcomms2-3
	zynq-zed-adv7511-ad9364-fmcomms4
	zynq-zed-adv7511-ad9467-fmc-250ebz
	zynq-zed-adv7511-cn0363
	zynq-zed-adv7511
	zynq-zed-adv7511-fmcmotcon2
	zynq-zed-imageon
	zynqmp-zcu102-rev10-ad9361-fmcomms2-3
	zynqmp-zcu102-rev10-ad9361-fmcomms5
	zynqmp-zcu102-rev10-ad9364-fmcomms4
	zynqmp-zcu102-rev10-adrv9008-1
	zynqmp-zcu102-rev10-adrv9008-2
	zynqmp-zcu102-rev10-adrv9009
	zynqmp-zcu102-rev10-adrv9371
	zynqmp-zcu102-rev10-fmcdaq2
	zynqmp-zcu102-rev10-fmcdaq3

For the zynq projects - copy target/BOOT.BIN, target/devicetree.dtb
and zynq-common/uImage to the root of the BOOT FAT32 partition.

For the zynqmp projects - copy target/BOOT.BIN, target/system.dtb
and zynqmp-common/Image to the root of the BOOT FAT32 partition.

For socfpga - copy all the files located in
the project's folder to the root of the BOOT FAT32 partition and
write the preloader_bootloader image to the corresponding SD card
partition (e.g., "dd if=preloader_bootloader.bin of=/dev/mmcblk0p3").

