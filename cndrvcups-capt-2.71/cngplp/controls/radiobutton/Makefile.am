noinst_LTLIBRARIES=libcaptradiobutton.la

libcaptradiobutton_la_SOURCES=radiobutton.c radiobutton.h

INCLUDES=-I$(top_srcdir)/cngplpmod\
	 -I$(top_srcdir)\
	 -I/usr/include/libxml2\
         @PACKAGE_CFLAGS@\
         @GLADE_PACKAGE_CFLAGS@

AM_CFLAGS=-Wall -O2 -fPIC
libcaptradiobutton_la_LIBADD= -lxml2 -lglade-2.0
