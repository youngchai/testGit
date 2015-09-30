CC = gcc
CFLAGS = -g -Wall -I../include
OUTPUT = main

$(OUTPUT): player.o
	$(CC) -o $(OUTPUT) $(CFLAGS) -L../lib player.o -lfuncs


player.o: player.c
	$(CC) -o player.o $(CFLAGS) -c player.c

clean:
	rm *.o $(OUTPUT)
