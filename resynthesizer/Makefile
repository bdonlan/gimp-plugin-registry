SRCDIR=bootchk-resynthesizer-0db24a9
TARFILE=$(SRCDIR).dfsg.tar.gz

include ../common-autotools.mk

$(SRCDIR)/configure: unpack-stamp

unpack-stamp:
	tar xzvf $(TARFILE)
	touch unpack-stamp

clean::
	rm -rf $(SRCDIR) unpack-stamp
