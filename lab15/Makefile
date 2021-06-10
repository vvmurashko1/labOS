all: server client client2

server: server.c common.h
	gcc server.c -o server

client: client.c common.h
	gcc client.c -o client
	gcc client2.c -o client2

clean:
	-rm server client *.o
