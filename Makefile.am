ACLOCAL_AMFLAGS = -I m4
SUBDIRS = src doc pixmaps data po

install-data-local:
	@$(NORMAL_INSTALL)
	$(INSTALL_DATA) $(top_srcdir)/AUTHORS $(DESTDIR)$(pkgdatadir)
	$(INSTALL_DATA) $(top_srcdir)/NEWS $(DESTDIR)$(pkgdatadir)
	$(INSTALL_DATA) $(top_srcdir)/README $(DESTDIR)$(pkgdatadir)

EXTRA_DIST = \
	autogen.sh            \
	intltool-extract.in   \
	intltool-merge.in     \
	intltool-update.in    \
	win32/config.mk       \
	win32/goocanvasprivate.h \
	win32/gpredict.rc        \
	win32/Makefile           \
	win32/icons/gpredict-icon.ico
