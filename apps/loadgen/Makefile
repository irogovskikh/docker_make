WORKDIR = ../../build
CC = gcc
CPPFLAGS = -I ../../include
all:
	mkdir -p $(WORKDIR)/apps/
	$(CC) $(CPPFLAGS) main.c stats.c $(WORKDIR)/lib/libcommon.a -o $(WORKDIR)/apps/loadgen
clean:

