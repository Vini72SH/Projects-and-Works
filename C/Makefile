CC = gcc
LDFLAGS = -lm
CFLAGS = -Wall -Werror -Wextra -g
SOURCES = $(wildcard *.c)
TARGETS = $(SOURCES:.c=)

all: $(TARGETS)

%: %.c
	$(CC) $(CFLAGS) -o $@ $<

clean:
	rm -f $(TARGETS)

.PHONY: clean

