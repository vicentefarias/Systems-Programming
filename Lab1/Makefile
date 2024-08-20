# Makefile for lab 1 part 1
#

CC  = gcc
CXX = g++

INCLUDES = 
CFLAGS   = -g -Wall $(INCLUDES)
CXXFLAGS = -g -Wall $(INCLUDES)

LDFLAGS = 
LDLIBS = 

.PHONY: default
default: convert printf-test

convert: convert.o

printf-test: printf-test.o



.PHONY: clean
clean:
	rm -f *.o *~ a.out core convert printf-test

.PHONY: all
all: clean default
