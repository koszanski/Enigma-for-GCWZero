Enigma-for-RetroFW
==================

Port of Enigma puzzle game to RetroFW devices.

Requirements:
sdl, sdl_mixer, sdl_image, sdl_ttf
libxerces
libpng
libcurl.

imagemagick, gettext



Config string used, ymmv with different toolchains: 

`./configure --build=x86_64 --host=mipsel-buildroot-linux-uclibc --includedir=/opt/buildroot/output/host/usr/mipsel-buildroot-linux-uclibc/sysroot/usr/include --prefix=/opt/buildroot/output/host/usr/mipsel-buildroot-linux-uclibc/sysroot/usr --sysconfdir=/opt/buildroot/output/host/etc --with-sysroot=/opt/buildroot/output/host/usr/mipsel-buildroot-linux-uclibc/sysroot --with-sdl-exec-prefix=/opt/buildroot/output/host/usr/mipsel-buildroot-linux-uclibc/sysroot/usr`

`make && make install`

Your data files are in /opt/buildroot/output/host/usr/mipsel-buildroot-linux-uclibc/sysroot/usr/share/enigma.
Your binary is in /opt/buildroot/output/host/usr/mipsel-buildroot-linux-uclibc/sysroot/usr/bin.
