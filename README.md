# CP2-F04-Team-Programming
# Work with a team to make a plan and code a dice roller



#Ben Walz
#Dice Roller 

#import
import random


#Def
def dice_roll():
    
    
    total = 0
    rolls = int(input("How many die do you want to roll? "))
    if rolls <= 0:
        print("you have to roll atleast 1 die")
    elif rolls > 0:
        while rolls > 0:
           rolled = random.randint(1, 6)
           total = rolled + total
           rolls = rolls - 1
           if rolls == 0:
               print("You rolled", total,)
    else:
        print("The input has to be a number")
           
           
           
     
        
        
        


dice_roll()
