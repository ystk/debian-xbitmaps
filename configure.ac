AC_PREREQ([2.57])
AC_INIT(xbitmaps, [1.1.0], [https://bugs.freedesktop.org/enter_bug.cgi?product=xorg], xbitmaps)
AM_INIT_AUTOMAKE([dist-bzip2])
AM_MAINTAINER_MODE

AM_CONFIG_HEADER(config.h)

# Require xorg-macros 1.3 or later: XORG_DEFAULT_OPTIONS
m4_ifndef([XORG_MACROS_VERSION],
	  [m4_fatal([must install xorg-macros 1.3 or later before running autoconf/autogen])])
XORG_MACROS_VERSION(1.3)
XORG_DEFAULT_OPTIONS

AC_OUTPUT([
	Makefile
	xbitmaps.pc
])
