
.PHONY:clean
	
all:example-client example-server

example-client:example-client.c
	gcc example-client.c -I. -o example-client -lpthread -L. -lwebsockets

example-server:example-server.c
	gcc example-server.c -I. -o example-server -L. -lwebsockets

clean:
	-rm example-client example-server
