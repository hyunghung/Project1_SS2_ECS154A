# Project1_SS2_ECS154A

## About
Name:
Student ID: 

## Description

### Main
On here, for Circuit 1, I attached a constant to the input to act as the values being compared, and to the output I added a LED that lights up green when the values are either 'Equal' or 'Not_Equal'

For circuit 2,


For circuit 3, for the inputs I added a pin to quickly change the inputs, running them through the logic gates created, and outputting a 1 input that would determine which segement within the 7-Segment Display to turn on.
### Circuit 1
Everything works. Essentially what was done here was a XNOR gate attached with an AND gate to compared the two bits together. XNOR acts as a comparsion unit between the two numbers, as it produces a high output when both values are the same and low output when both are different. Along with that, it was attached to an AND gate to make sure the bits are equal to each other. 

### Circcuit 2 


### Circuit 3 
Everything works. This containts a bunch of AND and OR gates that works together to produce an output. Example of this is with the TWO output, the horizontal line (Z) needed to be off, and any of the verticle lines could be on. Given that information, I had most of the possible combinations that could be in, attached them to an OR gate, which then went into an XOR gate. Within the XOR gate, it determines if at most 2 lines are on. If more than 2 is turned on, it wont pass the XOR gate. 