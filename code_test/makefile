LIBS  = 
CFLAGS = -Wall

# Should be equivalent to your list of C files, if you don't build selectively
SRC:=$(wildcard *.c)
EXE:=$(shell basename $(CURDIR))

all: $(EXE)

$(EXE): $(SRC)
	gcc $< $(LDFLAGS) $(CFLAGS) -o $@

clean:
	rm $(EXE) 2> /dev/null
