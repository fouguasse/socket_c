
OBJS = monocypher.o  main.o  
# Cpp:  C = g++ 
# C :	CC = gcc 
##CC = g++ 
CC = gcc -std=c++11 
CFLAGS = -Wall -O -g  
    
client : $(OBJS)  
	$(CC) $(OBJS) -o client  
 
    
clean:  
	rm -rf *.o client  

