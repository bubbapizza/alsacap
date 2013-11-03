# Include the pod file in the distribution.  If we don't do this, then
# the make files bark when building from a distribution tarball.
EXTRA_DIST = alsacap.pod

# Here is where we build the man file from pod.
dist_man_MANS = alsacap.1

alsacap.1: alsacap.pod
	pod2man --release='$(PACKAGE_VERSION)' --center='$(PACKAGE_NAME)' \
	   --section=1 $< > $@

CLEANFILES = alsacap.1

