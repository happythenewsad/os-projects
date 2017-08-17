# I am a comment, and I want to say that the variable CC will be
# the compiler to use.
CC=g++
# Hey!, I am comment number 2. I want to say that CFLAGS will be the
# options I'll pass to the compiler.
CFLAGS=-c -Wall -pthreads

all: main.o

main.o: main.cpp
	$(CC) $(CFLAGS) main.cpp -o a.out

clean:
	rm a.out
