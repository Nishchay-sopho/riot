MODULE = ieee802154

SRC = \
    ieee802154.c \
    #

ifneq (,$(filter ieee802154_submac,$(USEMODULE)))
	SRC += submac.c
endif

include $(RIOTBASE)/Makefile.base
