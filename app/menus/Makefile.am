## Process this file with automake to produce Makefile.in

AM_CPPFLAGS = \
	-DG_LOG_DOMAIN=\"Gimp-Menus\"	\
	-I$(top_builddir)		\
	-I$(top_srcdir)			\
	-I$(top_builddir)/app		\
	-I$(top_srcdir)/app		\
	$(GEGL_CFLAGS)			\
	$(GTK_CFLAGS)			\
	-I$(includedir)

noinst_LIBRARIES = libappmenus.a

libappmenus_a_SOURCES = \
	menus-types.h		\
	menus.c			\
	menus.h			\
	dockable-menu.c		\
	dockable-menu.h		\
	file-menu.c		\
	file-menu.h		\
	filters-menu.c		\
	filters-menu.h		\
	image-menu.c		\
	image-menu.h		\
	plug-in-menus.c		\
	plug-in-menus.h		\
	tool-options-menu.c	\
	tool-options-menu.h	\
	window-menu.c		\
	window-menu.h		\
	windows-menu.c		\
	windows-menu.h
