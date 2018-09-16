INCLUDES = $(all_includes)
METASOURCES = AUTO
noinst_HEADERS = librtf.h parser.h processor.h
include_HEADERS = textproc.h librtf.h
lib_LTLIBRARIES = librtf.la
librtf_la_SOURCES = convert.c librtf.c parser.c rtfproc.c
librtf_la_LDFLAGS = -no-undefined -version-number $(LIBRTF_VERSION_INFO)
