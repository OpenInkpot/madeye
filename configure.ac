AC_PREREQ(2.57)
AC_INIT(madeye, 0.1, lunohod@openinkpot.org)
AM_INIT_AUTOMAKE(foreign)

AC_PROG_CC_C99
PKG_PROG_PKG_CONFIG

PKG_CHECK_MODULES(EFL,[ecore ecore-file evas ecore-evas efreet-mime edje])
PKG_CHECK_MODULES(LIBKEYS,[libkeys])
PKG_CHECK_MODULES(LIBEOI,[libeoi])
PKG_CHECK_MODULES(LIBCHOICEBOX,[libchoicebox])

AC_OUTPUT(Makefile src/Makefile data/Makefile po/Makefile themes/Makefile help/Makefile)
