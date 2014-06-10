CC = gcc
CFLAGS = -c -g -Wall

all : tcp_server

tcp_server : main.o
	$(CC) main.o -o tcp_server

main.o : main.c
	$(CC) $(CFLAGS) main.c

clean : 
	rm -rf *o test