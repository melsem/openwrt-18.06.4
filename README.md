# openwrt-18.06.4
* Pоутеры с новым железом 
- ramips
- **[Kyan KY928A. rt5350 flash 4Mb, DDR1-32Mb, USB2.0](http://cyber-place.ru/showpost.php?p=38180&postcount=340)** и следующие сообщения.
- **[Outengda-M810 WPL6036. MT7620 flash 4-8Mb, DDR2-64Mb, USB есть, но только питание.](http://cyber-place.ru/showpost.php?p=39138&postcount=319)**
- **[WD7620N-R1-V1. MT7620 flash 4Mb, DDR1-32Mb, USB2.0](http://cyber-place.ru/showpost.php?p=41710&postcount=337)**
- **[KYAN-300M. MT7628 flash 8Mb, DDR2-64Mb, USB2.0](http://cyber-place.ru/showpost.php?p=41711&postcount=338)**

* Sunxi
- **[Orange-pi-zero - включены Wifi, soc-audio, 1Wire](http://4pda.ru/forum/index.php?showtopic=782242&st=3960#entry84352989)**
* =====================================

  _______                     ________        __
 |       |.-----.-----.-----.|  |  |  |.----.|  |_
 |   -   ||  _  |  -__|     ||  |  |  ||   _||   _|
 |_______||   __|_____|__|__||________||__|  |____|
          |__| W I R E L E S S   F R E E D O M
 -----------------------------------------------------

This is the buildsystem for the OpenWrt Linux distribution.

To build your own firmware you need a Linux, BSD or MacOSX system (case
sensitive filesystem required). Cygwin is unsupported because of the lack
of a case sensitive file system.

You need gcc, binutils, bzip2, flex, python, perl, make, find, grep, diff,
unzip, gawk, getopt, subversion, libz-dev and libc headers installed.

1. Run "./scripts/feeds update -a" to obtain all the latest package definitions
defined in feeds.conf / feeds.conf.default

2. Run "./scripts/feeds install -a" to install symlinks for all obtained
packages into package/feeds/

3. Run "make menuconfig" to select your preferred configuration for the
toolchain, target system & firmware packages.

4. Run "make" to build your firmware. This will download all sources, build
the cross-compile toolchain and then cross-compile the Linux kernel & all
chosen applications for your target system.

Sunshine!
	Your OpenWrt Community
	http://www.openwrt.org


