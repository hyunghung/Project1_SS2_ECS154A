# Project1_SS2_ECS154A

## About
Name: Anthony Nguyen

Student ID: 917534737

## Description

<u> ### Main </u>
On here, for Circuit 1, I attached a constant to the input to act as the values being compared, and to the output I added a LED that lights up green when the values are e>ither 'Equal' or 'Not_Equal'

For circuit 2, I used the 3th gray code. I attached a pin to add value to them, and it should output the correct correlating gray code. 


For circuit 3, for the inputs I added a pin to quickly change the inputs, running them through the logic gates created, and outputting a 1 input that would determine which segement within the 7-Segment Display to turn on.


<u> ### Circuit 1 </u>
Everything works. Essentially what was done here was a XNOR gate attached with an AND gate to compared the two bits together. XNOR acts as a comparsion unit between the two numbers, as it produces a high output when both values are the same and low output when both are different. Along with that, it was attached to an AND gate to make sure the bits are equal to each other. 

<u> ### Circcuit 2  </u>
I made it super simple, without simplying anything. Added an AND gate to every single possible values, attached them to an OR gate to determine which ones to use, which then is attached to G3, G2, G1, G0. All of the possbile zeros are attached to a ground output, that leads ensures the high comes from the AND gates and low comes from the ground. 

<u> ### Circuit 3 </u>
Everything works. This containts a bunch of AND and OR gates that works together to produce an output. Example of this is with the TWO output, the horizontal line (Z) needed to be off, and any of the verticle lines could be on. Given that information, I had most of the possible combinations that could be in, attached them to an OR gate, which then went into an XOR gate. Within the XOR gate, it determines if at most 2 lines are on. If more than 2 is turned on, it wont pass the XOR gate. 