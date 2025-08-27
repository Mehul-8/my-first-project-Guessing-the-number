# my-first-project-Guessing-the-number

import numpy as np

var=np.random.randint(1,100,1)

guess_number=int(input("enter the number:"))

if(guess_number==var):
    print("RIGHT GUESS")
else:
    print("TRY AGAIN")
