PROG=SHA2Words
SRCS=SHA2Words.c SHA2.c
OBJS=SHA2Words.o SHA2.o

IDENT_OPTS="-v -nip"

all: $(PROG)

$(PROG): $(OBJS)
    gcc -o $@ $(OBJS)

clean::
    rm -f $(PROG) $(OBJS)

indent::
    indent $(INDENT_OPTS) < SHA2Words.c
