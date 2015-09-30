CC = gcc
CFLAGS = -g -Wall -I../include
.SUFFIXES: .c .o
OUTPUT = libfuncs.a

$(OUTPUT): func1.o func2.o
	ar rv libfuncs.a func1.o func2.o

.c.o:
	$(CC) $(CFLAGS) -c $< -o $@

clean:
	rm *.o $(OUTPUT)
