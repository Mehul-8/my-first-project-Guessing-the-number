# my-first-project-Guessing-the-number
This is my first ever project on github. It is about guessing the correct number.
import numpy as np

var=np.random.randint(1,100,1)

guess_number=int(input("enter the number:"))

if(guess_number==var):
    print("RIGHT GUESS")
else:
    print("TRY AGAIN")
