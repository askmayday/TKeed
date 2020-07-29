objects = main.o util.o epoll.o http.o http_parse.o http_request.o priority_queue.o rio.o timer.o threadpool.o

CC = gcc -std=gnu99

TKeed:$(objects) 
	$(CC) $(objects) -pthread -o TKeed


clean : 
	rm $(objects) TKeed
