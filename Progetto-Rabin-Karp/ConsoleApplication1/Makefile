all: a.out

a.out:  Rabin-Karp.o main.o
	g++ -o a.out  Rabin-Karp.o main.o

Rabin-Karp.o: Rabin-Karp.cpp Search.h
	g++ -c Rabin-Karp.cpp

main.o: Rabin-Karp.cpp main.cpp
	g++ -c Rabin-Karp.cpp
	g++ -c main.cpp
