# Hello-Portfolio
# A number guessing game

import random 
 computerchoice = random.randint(1,100)
# The randint() method returns an integer number selected element from the specified range.
score = 0
while score != 1:
  guess = int(input("guess the number that the computer has chosen from 1-100"))
    if guess == computerchoice:
    print("You have chosen the correct number")
    score = score + 1 
  elif  guess > computerchoice:
    print("You number is too high")
  else:
    print("Your number is too low  enough)
