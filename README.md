buildroot_sis550
================

Buildroot snapshot containing configuration files needed to generate the kernel and the rootfs for the Norhtec's MicroClient Jr (SBC using SiS550 aka Vortex86)

To build the default image for this SBC please type:
make microclient_jr_defconfig
make

At the end, in the "images" directory you should have the kernel and the rootfs
