# Automake file

lib_LTLIBRARIES = libcppunitlite.la

libcppunitlite_la_SOURCES = src/Failure.cpp \
                            src/SimpleString.cpp \
                            src/Test.cpp \
                            src/TestRegistry.cpp \
                            src/TestResult.cpp

pkginclude_HEADERS = include/cppunitlite/Failure.h \
                     include/cppunitlite/SimpleString.h \
                     include/cppunitlite/Test.h \
                     include/cppunitlite/TestHarness.h \
                     include/cppunitlite/TestRegistry.h \
                     include/cppunitlite/TestResult.h

AM_CPPFLAGS = -I$(srcdir) -I$(srcdir)/include
