.PHONY: all

foo = $(bar)
bar = $(ugh)
ugh = Huh?

CFLAGS = $(include_dirs) -O

cflags = $(cflags) - O

include_dirs = -Ifoo -Ibar

all:
	@echo $(foo)

cflags:
	@echo $(CFLAGS)

loop:
	@echo $(cflags)


