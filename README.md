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

3.   Write a program that requests the current time and a waiting time as two integers for the number of hours and the number of minutes to wait. The program then outputs what the time will be after the waiting period. Use 24-hour notation for the times. Include a loop that lets the user repeat this calculation for additional input values until the user says she or he wants to end the program.
    Example of the output:

Compute completion time from current time and waiting period
Current time:
Enter 24 hour time in the format HH:MM
12:30
Waiting time:
Enter 24 hour time in the format HH:MM
15:40
Enter Y or y to continue, any other halts

y
Current time:
Enter 24 hour time in the format HH:MM
8:30
Waiting time:
Enter 24 hour time in the format HH:MM
15:10
Completion Time in 24 hour format:
23:40


Enter Y or y to continue, any other halts

n
Press any key to continue

