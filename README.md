INET 3101 - Lab 1.5

Dynamic Memory Allocation Program

Overview
- This program lets users enter numbers dynamically. It starts with a set memory size and grows as needed using realloc().

How to Run:
- Compile the program ( gcc 3-dynamically-allocating.c -o dynamic )
- Run it ( ./dynamic (number) )
- Enter numbers

Features
- Expands memory when needed
- Tracks only valid inputs
- Stops on non-integer input
- Frees memory before exiting

Example:
$ ./dynamic 5
Please enter numbers:
1
2
3
4
5
6
q
Output:
- Numbers in the array:
1 2 3 4 5 6
