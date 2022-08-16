THISDIR := $(shell pwd)


all: 
	@echo "tailscale build ok!"

clean:
	@echo "tailscale clean ok!"

romfs:
	$(ROMFSINST) -p +x $(THISDIR)/tailscale /usr/bin/tailscale
	$(ROMFSINST) -p +x $(THISDIR)/tailscaled /usr/bin/tailscaled
