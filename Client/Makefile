
OBJS = main.o  
# Cpp:  C = g++ 
# C :	CC = gcc 
##CC = g++ 
CC = gcc -std=c++11 
CFLAGS = -Wall -O -g  
    
#helloworld : $(OBJS)  
#	$(CC) $(OBJS) -o helloworld  
client : $(OBJS)  
	$(CC) $(OBJS) -o client  
    
#file1.o : file1.c file2.h  
#    $(CC) $(CFLAGS) -c file1.c -o file1.o  
    
#file2.o : file2.c file2.h  
#    $(CC) $(CFLAGS) -c file2.c -o file2.o  
    
clean:  
	rm -rf *.o client  

