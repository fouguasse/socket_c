
OBJS = monocypher.o main.o  
# Cpp:  C = g++ 
# C :	CC = gcc 
##CC = g++ 
CC = gcc -std=c++11 
CFLAGS = -Wall -O -g  

server : $(OBJS)  
	$(CC) $(OBJS)  -o server     
    
clean:  
	rm -rf *.o server  

