
include $(top_srcdir)/aminclude_static.am

AM_CPPFLAGS = \
	$(CODE_COVERAGE_CPPFLAGS) \
    -Wall \
    -I$(top_srcdir)/src/ \
    -I$(top_srcdir)/src/fmtlib

AM_LIBS = $(CODE_COVERAGE_LIBS)
AM_CFLAGS = $(CODE_COVERAGE_CFLAGS)
AM_CXXFLAGS = $(CODE_COVERAGE_CXXFLAGS)

noinst_LIBRARIES = libbase.a

noinst_HEADERS = \
    date_time_scanner.hh \
    enum_util.hh \
    file_range.hh \
    func_util.hh \
    future_util.hh \
	humanize.hh \
	injector.hh \
	injector.bind.hh \
	intern_string.hh \
    is_utf8.hh \
    isc.hh \
    lnav_log.hh \
    math_util.hh \
    opt_util.hh \
    result.h \
    string_util.hh \
    time_util.hh

libbase_a_SOURCES = \
    date_time_scanner.cc \
	humanize.cc \
	intern_string.cc \
    is_utf8.cc \
    isc.cc \
    lnav_log.cc \
    string_util.cc \
    time_util.cc
