ECE281_CE4
==========

Computer Exercise 4

# Part A

This part was pretty straight forward. We were supposed to load and store 3 seperate values in different locations. The part I 
ran into trouble at was placing the operands into the RAM section below the ROM section of the program. Once I realized that
that was where you placed the locations to store the values, it made the program a lot easier. 

# Part B

This part was also relatively straight forward. We had to perform math on the value retrieved from the memory. At first, I forgot to enable RAM to be edited, so that presented some problems. Then I tried to load 4 into the accumulator and then use 2's compliment to add to mem1, but I ran into some problems and was able to simplify it down to output mem1*2-4. 

# Part C

First, I input 5 into port 3. This program is supposed to continuously subtract 1 from the previous value. I then added and F, which is hex for -1. After that, I added one which would essentially make the program subtract 1 from the initial value, which is what the program is supposed to do. At the end, I added a jmp, but I did not want it to jump back to the beginning and start with the input, so I had it jmp back to address 04. 
