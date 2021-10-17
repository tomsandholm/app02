bin_PROGRAMS = app02
app01_SOURCES = app02.c

package:
	sudo checkinstall -D --default --strip=yes --install=no --pkgname $(bin_PROGRAMS)

clean-local:
	sudo checkinstall uninstall $(bin_PROGRAMS)
