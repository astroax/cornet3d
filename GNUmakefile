# This is a GNU make file that uses GNU make make extensions


BUILD_NO_INSTALL := cornet3d_webServer

# How to build it
cornet3d_webServer:
	ln -fs lib/$@ $@

include ./quickbuild.make

ifneq ($(srcdir),.)
  #$(error You cannot srcdir=$(srcdir)  build this from outside the source tree)
endif
