test: memlib.o mm.o test.o
	gcc test.o memlib.o mm.o -o test

memlib.o: memlib.c memlib.h
	gcc memlib.c -c -g

mm.o: mm.c mm.h
	gcc mm.c -c -g

test.o: test.c
	gcc test.c -c -g
