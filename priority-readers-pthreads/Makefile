# I am a comment, and I want to say that the variable CC will be
# the compiler to use.
CC=clang
# Hey!, I am comment number 2. I want to say that CFLAGS will be the
# options I'll pass to the compiler.
CFLAGS= -Wall -pthreads

# using the -c flag will stop clang from creating an executable

all: main.c
	$(CC) $(CFLAGS) main.c -o main 

clean:
	rm a.out
