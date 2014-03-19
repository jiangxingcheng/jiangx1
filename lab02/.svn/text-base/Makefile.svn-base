# Student's Makefile for the Bit-Level Data Representation Lab

CC = gcc
CFLAGS = -g #-O -Wall

btest: btest.c bits.c decl.c tests.c btest.h bits.h
	$(CC) $(CFLAGS) -o btest bits.c btest.c decl.c tests.c

clean:
	rm -f *.o btest
