# Dice-generator
Making a 5 dice , dice generator  with help of python
import random 

dice = []
for i in range(5):
    dice.append(random.randint(1,6))
    print(f"Dice {i+1}: "+str(dice[i]))
    
print("Total sum = " + str(sum(dice)))
   
