RPi-LTIB
========

LTIB files needed for Raspberry Pi support.

The Linux Target Image Builder (LTIB) prefers its toolchains to be in an
RPM file, rather than laid out in a git repository.  This repository
contains files from the official Raspberry Pi repository
(https://github.com/raspberrypi/), but packaged in an LTIB-friendly
manner.

The file you want is probably this one:

https://github.com/downloads/midnightyell/RPi-LTIB/raspberrypi-tools-9c3d7b6-1.i386.rpm

Which is the packaged version of the toolchain binaries found in
https://github.com/raspberrypi/tools/commit/9c3d7b6ac692498dd36fec2872e0b55f910baac1

These appear to be gcc-4.7.1 toolchains that were produced with
crosstool-ng 1.15.2, using the config files found at
https://github.com/raspberrypi/tools/tree/master/configs

All questions about the RPM package file should be directed to me.  Any
questions about the compilers contained in the package should be
directed towards the maintainer of  https://github.com/raspberrypi.

