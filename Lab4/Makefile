# Makefile for lab 4

CC  = gcc
CXX = g++

INCLUDES = 
CFLAGS   = -g -Wall $(INCLUDES)
CXXFLAGS = -g -Wall $(INCLUDES)

LDFLAGS = 
LDLIBS = 

.PHONY: default
default: mdb-lookup-server-nc-1 mdb-lookup-server-nc-2

mdb-lookup-server-nc-1: mdb-lookup-server-nc-1.o

mdb-lookup-server-nc-2: mdb-lookup-server-nc-2.o


.PHONY: clean
clean:
	rm -f *.o *~ a.out core mdb-lookup-server-nc-1 mdb-lookup-server-nc-2

.PHONY: all
all: clean default