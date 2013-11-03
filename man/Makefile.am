#EXTRA_DIST = alsacap.pod
dist_man_MANS = alsacap.1

alsacap.1: alsacap.pod
	pod2man --release='$(PACKAGE_VERSION)' --center='$(PACKAGE_NAME)' \
	   --section=1 $< > $@

CLEANFILES = alsacap.1

