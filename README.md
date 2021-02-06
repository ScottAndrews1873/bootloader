This repository contains pre-compiled binaries of the current Raspberry Pi 
kernel and modules, userspace libraries, and bootloader/GPU firmware.

A rough guide to this repository and the licences covering its contents is 
below (check the appropriate directories for more specific licence details):

* boot:
    * start*.elf, fixup*.dat and bootcode.bin are the GPU firmwares and
    bootloader. Their licence is described in `boot/LICENCE.broadcom`.
    * The kernel.img files are builds of the Linux kernel, released under the GPL
    (see `boot/COPYING.linux`)
* documentation/ilcomponents: OpenMax IL documentation (`boot/LICENCE.broadcom`)
