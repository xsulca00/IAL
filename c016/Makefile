
PRJ=c016
#
PROGS=$(PRJ)-test
CC=gcc
CFLAGS=-Wall -std=c99 -g -pedantic -lm

all: $(PROGS)

$(PRJ)-test: $(PRJ).c $(PRJ)-test.c
	$(CC) $(CFLAGS) -o $@ $(PRJ).c $(PRJ)-test.c

clean:
	rm -f *.o *.out $(PROGS)
#
