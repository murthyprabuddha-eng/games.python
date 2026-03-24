# games.python
1-guess the number
import random
num=random.randint(1,10)
print("geuss the number between 1 and 10")
guess=int(input("number: "))
while num!=guess:
    if num>guess:
        print(" higher guess again")
    else:
        print("lower guess again")
    guess=int(input("number: "))

print(" right guess the number was", num)
    
