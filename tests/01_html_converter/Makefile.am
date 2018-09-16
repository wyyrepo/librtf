INCLUDES = -I$(top_srcdir)/src/cpp
METASOURCES = AUTO

01_html_converter_SOURCES = html.cpp
01_html_converter_LDFLAGS = -all-static


noinst_PROGRAMS = test_01_rtf2html
test_01_rtf2html_SOURCES = html.cpp
test_01_rtf2html_LDADD = $(top_builddir)/src/cpp/librtfcpp.la\
	$(top_builddir)/src/c/librtf.la
