testprog: main.o
	$(LINK.c) -o testsprog main.o

main.o: main.c header.h
	$(COMPILE.c) main.c

clean:
	$(RM) main.o testprog

lint: main.c header.h
	$(LINT) main.c
