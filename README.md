# fc-functions-assignments

1.  Define a function named CoinFlip that returns "Heads" or "Tails" according to a random value 1 or 0. Assume the value 1 represents "Heads" and 0 represents "Tails". Then, write a main program that reads the desired number of coin flips as an input, calls function CoinFlip() repeatedly according to the number of coin flips, and outputs the results. Assume the input is a value greater than 0.

Hint: Use the modulo operator (%) to limit the random integers to 0 and 1.

Ex: If the random seed value is 2 and the input is:

3

The output is:

Tails
Heads
Tails

The program must define and call the following function:
string CoinFlip()


2.   You have invented a vending machine capable of deep frying twinkies. Write a program to simulate the vending machine. It costs $3.50 to buy a deep-fried twinkie, and the machine only takes coins in denominations of a dollar, quarter, dime, or nickel. Write code to simulate a person putting money into the vending machine by repeatedly prompting the user for the next coin to be inserted. Output the total entered so far when each coin is inserted. When $3.50 or more is added, the program should output “Enjoy your deep-fried twinkie” along with any change that should be returned. Use top-down design to determine appropriate functions for the program.
