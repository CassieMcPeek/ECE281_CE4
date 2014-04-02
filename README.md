ECE281_CE4
==========

Computer Exercise 4

# Part A

This part was pretty straight forward. We were supposed to load and store 3 seperate values in different locations. The part I 
ran into trouble at was placing the operands into the RAM section below the ROM section of the program. Once I realized that
that was where you placed the locations to store the values, it made the program a lot easier. 

# Part B

This part was also relatively straight forward. We had to perform math on the value retrieved from the memory. At first, I forgot to enable RAM to be edited, so that presented some problems. Then I tried to load 4 into the accumulator and then use 2's compliment to add to mem1, but I ran into some problems and was able to simplify it down to output mem1*2-4. 
