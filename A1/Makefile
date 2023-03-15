all: Part1_driver.o Part2_driver.o
	gcc Part1_driver.o Part2_driver.o

Part1_driver.o:
	gcc -Wall -Wextra -c Part1_driver.c
Part2_driver.o:
	gcc -Wall -Wextra -c Part2_driver.c

clean:
	rm -f a.out Part1_driver.o Part2_driver.o
