CC = gcc
CPPFLAGS = -I ../../include
WORKDIR = ../../build
all:
	mkdir -p $(WORKDIR)/apps/
	$(CC) $(CPPFLAGS) main.c router.c $(WORKDIR)/lib/libcommon.a -o $(WORKDIR)/apps/balancer
clean:

