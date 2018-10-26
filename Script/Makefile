#Makefile
#AUTHORS: antoine.montes

CC ?= gcc
CFLAGS = -Wall -Werror -Wextra -pedantic -std=c99 -g -fsanitize=address
LDFLAGS = -fsanitize=address

SRC = 
OBJ = $(SRC:.c=.o)

all:


check: $(OBJ)


clean:
	rm -f $(OBJ) check
