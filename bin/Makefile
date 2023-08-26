# Makefile reads top to bottom

# 'main.o' forces make to do main.o task first
main: main.o
	g++ -o main main.o greeting.o

main.o: greeting.o
	g++ -c main.c

greeting.o:
	g++ -c greeting.c greeting.h