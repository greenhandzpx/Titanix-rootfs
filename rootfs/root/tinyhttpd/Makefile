all: httpd

httpd: httpd.c
	musl-gcc -W -Wall -lpthread -static -o httpd httpd.c
	musl-gcc -W -Wall -lpthread -static -o simpleclient simpleclient.c
clean:
	rm httpd simpleclient
