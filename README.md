# cross-pi-gcc
Build a Cross-Toolchain for Raspberry Pi 3 from source

Because  this is from a project that i failed to submit on time... I decided to take it as a personal goal to make this work.

As a result of ~2-months research, trials and errors along the way... I finally been able to achieve what i need for my use case
 and now i'' share with everyone that may or may not be useful for you.
 
This is in no-way near to what a Linaro-Toolchain could do, but enough for my needs which are:
  1. A latest C/C++ cross-compiler for armhf Raspberry Pi 3.
  2. This must be able to be use as an alternative compiler for QT for Raspberry Pi. Linaro-7.4.1 which i use to previous projects.
    (also used the raspberrypi tools).

Future support/capability plans:
  1. Arm64
  2. Golang

Features:
 * BINUTILS_VER=__2.32__
 * GCC_VER=__8.3.0__
 * GLIBC_VER=__2.28__
 * LINUX_VER=__rpi-4.19.y__





#### Donation
You get the best out of others when you give the best of yourself. :)

[![paypal](https://www.paypalobjects.com/en_US/i/btn/btn_donateCC_LG.gif)](https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=MFLAEY2CXYTXG)

![QR paypal](https://raw.githubusercontent.com/a-DelaCruz/cross-pi-gcc/bc3e01e54bf90fccc3753686d3000d50e5d9fc07/QR_Code.png)
