noinst_LTLIBRARIES=libcaptentry.la

libcaptentry_la_SOURCES=entry.c entry.h

INCLUDES=-I$(top_srcdir)/cngplpmod\
	 -I$(top_srcdir)\
	 -I/usr/include/libxml2\
         @PACKAGE_CFLAGS@\
         @GLADE_PACKAGE_CFLAGS@

AM_CFLAGS=-Wall -O2 -fPIC
libcaptentry_la_LIBADD= -lxml2 -lglade-2.0
