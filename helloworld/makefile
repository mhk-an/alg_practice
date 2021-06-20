#Makefile

CC = g++

helloworld.out : helloworld.o
	g++ -o helloworld.out helloworld.o

helloworld.o : helloworld.cpp
	g++ -c -o helloworld.o helloworld.cpp

clean :
	rm -rf *.o *.out
