
EXTRA_DIST=              \
        README           \
        doom.ico         \
        doom8.ico        \
        doom.png         \
        setup.ico        \
        setup8.ico       \
        setup.png        \
        convert-icon

iconsdir = $(prefix)/share/icons/hicolor/128x128/apps
icons_DATA = @PROGRAM_PREFIX@doom.png   \
             @PROGRAM_PREFIX@setup.png

@PROGRAM_PREFIX@doom.png : doom.png
	cp $(top_srcdir)/data/doom.png $@

@PROGRAM_PREFIX@setup.png : setup.png
	cp $(top_srcdir)/data/setup.png $@

CLEANFILES = $(icons_DATA)
