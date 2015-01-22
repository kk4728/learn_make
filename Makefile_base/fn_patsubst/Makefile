.PHONY: all

#replace function
#parm:old pathern, replacement, name lists
#return:name lists after the replacement

mixed = foo.c bar.c main.o
objects := $(patsubst %.c, %.o, $(mixed))

all:
	@echo $(objects)
