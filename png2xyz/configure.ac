AC_INIT([png2xyz],[1.0],[https://github.com/EasyRPG/Tools/issues],[png2xyz],[https://easyrpg.org/])

AC_CONFIG_AUX_DIR([.])
AM_INIT_AUTOMAKE([foreign subdir-objects -Wall])
AM_SILENT_RULES([yes])

AC_CONFIG_SRCDIR([src/png2xyz.cpp])
AC_CONFIG_HEADERS([config.h])
AC_CONFIG_FILES([Makefile])

AC_PROG_CXX
PKG_CHECK_MODULES([PNG],[libpng])
PKG_CHECK_MODULES([ZLIB],[zlib])

AC_OUTPUT
