## Process this file with automake to generate Makefile.in

SUBDIRS = varconf doc tests

pkgconfigdir = $(libdir)/pkgconfig
pkgconfig_DATA = varconf-1.0.pc

EXTRA_DIST = autogen.sh varconf.spec.in varconf.spec ChangeLog-CVS generate-ChangeLog.sh

dist-hook:
	sh $(top_srcdir)/generate-ChangeLog.sh $(top_srcdir) $(distdir) c10bcf499ae5082832d878006e5c63a8421e9595