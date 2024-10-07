CC = gcc
CFLAGS = -c -g -Wall -Werror
OBJ = a1.o
DEPS = a1.c

all: a1 Assign1

a1: a1.o
	$(CC) -o a1 a1.o

Assign1: Assign1.o
	$(CC) -o Assign1 Assign1.o

a1.o: a1.c
	$(CC) $(CFLAGS) a1.c

Assign1.o: Assign1.c
	$(CC) $(CFLAGS) Assign1.c

clean:
	rm -f a1 Assign1 a1.o Assign1.o

