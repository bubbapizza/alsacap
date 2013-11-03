# This is for building the program.
bin_PROGRAMS = alsacap
AM_LDFLAGS = -lasound

# This is for building the man page.
bin_SCRIPTS = alsacap.pod
man_MANS = alsacap.1

alsacap.1: alsacap.pod
	pod2man --release='$(PACKAGE_VERSION)' --center='$(PACKAGE_NAME)' \
      --section=1 $< > $@

CLEANFILES = alsacap.1

