## Process this file with automake to produce Makefile.in -*-Makefile-*-
AUTOMAKE_OPTIONS = foreign 1.2h
                                                                                
EXTRA_DIST = Gnuplot.app-defaults

SUBDIRS = LaTeX

appdefaultdir = $(libdir)/X11/app-defaults

APPDEFAULTFILES = Gnuplot

appdefault_DATA = $(APPDEFAULTFILES)

Gnuplot: $(srcdir)/Gnuplot.app-defaults
	cp -p $(srcdir)/Gnuplot.app-defaults $@

CLEANFILES = $(APPDEFAULTFILES)
