SOURCES = host.c mab.c pcb.c rsrc.c tian_sigtrap.c
HEADERS = mab.h tian_pcb.h tian_rsrc.h types.h
CC = gcc
CFLAGS = -g -Wall

host: $(OBJECTS)
	$(CC) $(CFLAGS) $(OBJECTS) -o host

$(OBJECTS): $(HEADERS)
	
clean:
	rm -fR *o host