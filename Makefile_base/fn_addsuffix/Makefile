.PHONY: all

without_suffix = foo bar main
with_suffix := $(addsuffix .c, $(without_suffix))

all:
	@echo $(with_suffix)
