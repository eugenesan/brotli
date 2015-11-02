AC_PREREQ(2.57)

AC_INIT([libbrotli], [0.2.0], [-])
AC_CONFIG_SRCDIR([dec/decode.h])
AC_CONFIG_HEADERS([config/config.h])
AC_CONFIG_MACRO_DIR([config/m4])
LT_INIT
AM_INIT_AUTOMAKE()
AM_MAINTAINER_MODE
m4_ifdef([AM_SILENT_RULES], [AM_SILENT_RULES([yes])])

AC_PROG_CC
AC_PROG_CXX

AX_CXX_COMPILE_STDCXX_11([noext], [optional])

AC_CONFIG_FILES([Makefile config/libbrotlienc.pc config/libbrotlidec.pc])
AC_OUTPUT
