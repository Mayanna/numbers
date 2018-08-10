# numbers
#Name a number and let AI guess ... sublime text,python3.6

import random

print("pls print a number smaller than 10 let me guess if that is what you are thinking: \n")
numb=int(input())
guess=random.randint(1,10)
print("my first guess is ",guess)
i=1
judge = True

while judge:
	if guess == numb:
		print('I did it in ',i,' time(s)!'," It is ",guess)
		judge = False
	elif guess < numb:
		guess = guess * 2
		i=i+1
		print('Opps,try again')
	elif guess > numb:
		guess = int(guess / 2)
		i=i+1
		print('Opps,try again')	

