# control variables
CC=gcc
CFLAGS=-g -Wall
OBJS=main.o

.PHONY: all clean

all: $(OBJS)
  $(CC) $(CFLAGS) -o main $(OBJS)

%.o : %.c
   $(CC) $(CFLAGS) -c $< -o $@

clean: $(OBJS)
   rm -rf $(OBJS)