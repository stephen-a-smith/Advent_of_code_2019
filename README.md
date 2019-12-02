# Advent of code 2019

I will post my solutions to the Advent of code problems here, as well as post explaination for specefic choices made
I will try to make all solutions generally applicable, to be functional with arbitrary inputs, [mostly] regardless of length. As long as the input follows the rules of the problem given, these solutions should work.

Every program will be in C using the standard library. If I need to use extra header files they will all be provided and built myself.

# Day 1
__Part 1__
Simple enough, I pass the input through the command line and do the arithmetic required.

__Part 2__
I felt like a recursive approach made sense here, so that's the approach I took. Again, a simple problem, but it is still only day 1 after all.

# Day 2
__Part 1__
Good practice for Malloc and pointers, though maybe I have a little bit too much shared state. Most of the problems I had to manage when writing this came from the readFile() function, once I had that working everything was smooth sailing.

__Part 2__
Not much had to be changed here, In retrospect I would have saved some performance by instead of reading the file every time simply copying `*arr` to `*arr_original` or something along those lines, but I think the performance benefits wouldn't be very noticable. 
