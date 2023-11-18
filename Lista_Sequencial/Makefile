CC = g++
CPP_VERSION = -std=c++20

OBJS = lista.o main.o

programa: $(OBJS)
	$(CC) $(CPP_VERSION) $(OBJS) -o programa

lista.o: lista.cpp lista.h
	$(CC) $(CPP_VERSION) -c lista.cpp

main.o: main.cpp lista.h
	$(CC) $(CPP_VERSION) -c main.cpp
