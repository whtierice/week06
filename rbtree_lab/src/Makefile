.PHONY: clean

CFLAGS = -Wall -g -DSENTINEL 

driver: driver.o rbtree.o

driver.o: driver.c ../test/test-rbtree.c 

clean:
	rm -f driver *.o
