SUBDIRS = data glinject scripts src

man1_MANS = simplescreenrecorder.1 ssr-glinject.1

EXTRA_DIST = \
	AUTHORS.md \
	CHANGELOG.md \
	COPYING \
	notes.txt \
	postinstall \
	README.md \
	simple-build-and-install \
	simple-uninstall \
	simplescreenrecorder.1.in simplescreenrecorder.1 \
	ssr-glinject.1.in ssr-glinject.1 \
	todo.txt

ACLOCAL_AMFLAGS = -I m4

libtool: $(LIBTOOL_DEPS)
	$(SHELL) ./config.status libtool
