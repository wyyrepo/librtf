INCLUDES = -I$(top_srcdir)/src/c $(all_includes)
METASOURCES = AUTO

include_HEADERS = librtfcpp.h
noinst_HEADERS = librtfcpp.h
lib_LTLIBRARIES = librtfcpp.la
librtfcpp_la_SOURCES = librtfcpp.cpp
librtfcpp_la_LIBADD = $(top_builddir)/src/c/librtf.la
librtfcpp_la_LDFLAGS = -no-undefined -version-number $(LIBRTF_VERSION_INFO)
