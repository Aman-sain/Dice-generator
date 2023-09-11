# Dice-generator
Making a 5 dice , dice generator  with help of python
import random 

dice = []
for i in range(5):
    dice.append(random.randint(1,6))
    print(f"Dice {i+1}: "+str(dice[i]))
    
print("Total sum = " + str(sum(dice)))

1. Importing the random module: 

->The code begins by importing Python's built-in random module. This module provides functions for generating random numbers, which is essential for simulating the roll of a dice. 

2. Defining the roll_dice() function: 

->The roll_dice() function is defined to simulate the rolling of a standard six-sided dice. 

->Inside the function, it uses the random.randint(a, b) function to generate a random integer between 1 and 6 (inclusive) and assigns it to the number variable. 

->The function then returns this number, which represents the outcome of rolling the dice. 

 

 

3. Asking the user for input: 

->The program prompts the user to enter the number of times they want to roll the dice using the input() function. The input is converted to an integer and stored in the variable times. 

4. Initializing an empty list results: 

->An empty list named results is created to store the outcomes of the dice rolls. 

5. Rolling the dice as many times as specified: 

->A for loop is used to roll the dice the number of times specified by the user (stored in the times variable). 

->Inside the loop, the roll_dice() function is called, and the result (the outcome of the dice roll) is appended to the results list.   

6. Displaying the dice roll outcomes: 

->After all the dice rolls are completed, the program prints the results using print("Behold, the mystical dice have spoken! The results are:", results). 

7. Calculating the sum of the outcomes: 

->Another for loop is used to iterate through the results list, and the values are added together to calculate the sum of the dice roll outcomes. The sum is stored in the variable sum. 

8. Displaying the sum: 

->Finally, the program prints the sum of the dice roll outcomes using print("The sum of the dice's wisdom is:", sum).

9. Conclusion: 

->The program concludes with a friendly message, thanking the user for using the Magical Dice Roller. 

In summary, this Python program allows the user to simulate rolling a six-sided dice multiple times, records the outcomes, calculates the sum of those outcomes, and then displays the results to the user. It's a fun and simple example of using random number generation and basic control structures in Python.

10. Feedback:

We created a feedback form to gather feedback from a diverse group of people. This feedback form has been shared with students. Their responses and perspectives will provide valuable information to help us assess the project's effectiveness and identify areas for improvement.
