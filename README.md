# Hello-Portfolio
# A number guessing game
# The randint() method returns an integer number selected element from the specified range.

import random 
computerchoice = random.randint(1, 100)
score = 0
while score != 1:
    guess = int(input("Guess the number that the computer has chosen from 1-100: "))
    
    if guess == computerchoice:
        print("You have chosen the correct number")
        score = score + 1 
    elif guess > computerchoice:
        print("Your number is too high")
    else:
        print("Your number is too low")
