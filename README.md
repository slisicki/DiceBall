# DiceBall
Dice BaseBall Game
from random import randint

#create dictionary for die rolls
bd = {}
bd[1,1] = 'Home Run'
bd[1,2] ='Single'
bd[1,3] = 'Out' 
bd[1,4] = 'Double Play'
bd[1,5] = 'Out'
bd[1,6] = 'Out'
bd[2,1] = 'Single'
bd[2,2] = 'Walk'
bd[2,3] = 'Out'
bd[2,4] = 'Double'
bd[2,5] = 'Out'
bd[2,6] = 'Triple'
bd[3,1] = 'Out'
bd[3,2] = 'Out'
bd[3,3] = 'Strikeout'
bd[3,4] = 'Out'
bd[3,5] = 'Single'
bd[3,6] = 'Out'
bd[4,1] = 'Double Play'
bd[4,2] = 'Double'
bd[4,3] = 'Out'
bd[4,4] = 'Strikeout'
bd[4,5] = 'Single'
bd[4,6] = 'Out'
bd[5,1] = 'Out'
bd[5,2] = 'Out' 
bd[5,3] = 'Single'
bd[5,4] = 'Single'
bd[5,5] = 'Strikeout'
bd[5,6] = 'Out'
bd[6,1] = 'Out'
bd[6,2] = 'Triple'
bd[6,3] = 'Out'
bd[6,4] = 'Out'
bd[6,5] = 'Out'
bd[6,6] = 'Home Run'

Out = 0
#roll dice
roll_dice = 'r'
def roll_dice():
        dice1 = randint(1,6)
        dice2 = randint(1,6)
        mydice = dice1,dice2
        print (mydice)
        return mydice        

roll = roll_dice()

print (bd[roll])

def base_runners():
