ICONDIR = $(DESTDIR)/usr/local/share/jwm

ICONS = jwm.xbm jwm-gray.svg jwm-blue.svg jwm-orange.svg

install:
	install -d $(ICONDIR)
	for f in $(ICONS) ; do \
		install -m 0644 $$f $(ICONDIR)/$$f ; \
	done

uninstall:
	for f in $(ICONS) ; do \
		rm -f $(ICONDIR)/$$f ; \
	done
