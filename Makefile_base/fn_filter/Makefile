.PHONY: all

filter_t = foo.c bar.c baz.s ugh.h
filter_t := $(filter %.c %.s, $(filter_t))

filter_tt = foo.c bar.c baz.s ugh.h
filter_tt := $(filter-out %.c %.s, $(filter_tt))

all:
	@echo $(filter_t)
	@echo $(filter_tt)

