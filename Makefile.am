AUTOMAKE_OPTIONS = foreign

EXTRA_DIST = \
  CHANGES \
  CONTRIBUTORS

AM_CPPFLAGS = -I$(srcdir) -I$(srcdir)/include

# Build rules for libraries.
lib_LTLIBRARIES = lib/libcppunitlite.la

lib_libcppunitlite_la_SOURCES = src/Failure.cpp \
                                src/SimpleString.cpp \
                                src/Test.cpp \
                                src/TestRegistry.cpp \
                                src/TestResult.cpp
                                
pkginclude_HEADERS = include/Failure.h \
                     include/SimpleString.h \
                     include/Test.h \
                     include/TestHarness.h \
                     include/TestRegistry.h \
                     include/TestResult.h


