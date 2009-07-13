# $Id$

docdir = $(prefix)/share/doc/@PACKAGE@
doc_DATA = README INSTALL COPYING AUTHORS ChangeLog NEWS

cdbppincludedir = $(includedir)

cdbppinclude_HEADERS = \
	include/cdbpp.h

noinst_PROGRAMS = cdbpp-sample

cdbpp_sample_SOURCES = \
	sample/sample.cpp

EXTRA_DIST = \
	autogen.sh \
	win32/stdint.h \
	cdbpp.sln \
	sample/sample.vcproj
