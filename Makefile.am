SUBDIRS = src

# Install binaries and headers
bin_PROGRAMS = myprogram
myprogram_SOURCES = src/main.c src/func.c src/header.h

clean-all:
	rm -f $(bin_PROGRAMS)
	rm -f /usr/local/bin/$(bin_PROGRAMS)
	rm -f /usr/local/include/header.h
