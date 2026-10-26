CC = gcc
CPPFLAGS = -I ../include
CFLAGS = -c
WORKDIR = ../build
lib net.c http.c utils.c:
	mkdir -p $(WORKDIR)/lib
	$(CC) $(CPPFLAGS) $(CFLAGS) net.c -o $(WORKDIR)/lib/net.o
	$(CC) $(CPPFLAGS) $(CFLAGS) http.c -o $(WORKDIR)/lib/http.o
	$(CC) $(CPPFLAGS) $(CFLAGS) utils.c  -o $(WORKDIR)/lib/utils.o
	cd $(WORKDIR)/lib && ar rcs libcommon.a net.o http.o utils.o
clean:
	cd $(WORKDIR)/lib && rm -f *.o
