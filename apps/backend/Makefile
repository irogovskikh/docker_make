WORKDIR = ../../build
CC = gcc
CPPFLAGS = -I ../../include
all:
	mkdir -p $(WORKDIR)/apps/
	$(CC) $(CPPFLAGS) main.c handler.c $(WORKDIR)/lib/libcommon.a -o $(WORKDIR)/apps/backend
clean:

