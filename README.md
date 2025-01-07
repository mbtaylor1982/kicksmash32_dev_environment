# kicksmash32 dev environment

This is a image based on the official docker build of [Fedora 40](https://registry.hub.docker.com/layers/library/fedora/40/images/sha256-0dc52447068058c56588a816d43bd80d4279dcbefbb74f2aa55d2745413afbc1) and is intended to act as a dev environment for the [kicksmash32](https://github.com/cdhooper/kicksmash32) project by [Chris Hooper](https://github.com/cdhooper).

The image includes all the perquisites to build the software and firmware for the project including:

- [libopencm3](https://github.com/libopencm3/libopencm3) Open-source firmware library for various ARM Cortex-M microcontrollers.
- [stlink](https://github.com/stlink-org/stlink) Open source version of the STMicroelectronics STLINK Tools.
- [amiga-gcc](https://github.com/bebbo/amiga-gcc) The GNU C Compiler with binutils and other useful tools for cross compiling software for the Commodore Amiga.

