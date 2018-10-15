# Workshop2
Rolling Dice Game

We are creating a game of rolling the dice. 

**import random**  		#importing library to generate random numbers 

Numbers on dice are from 1 to 6, that is why we set min=1 and max=6.
**min = 1                                   **
**max = 6**

**roll_again = "yes"**

Using while loop, to create a case where user might want to play again.
Python works on indentation basis ( 4 spaces or 1 tab). So the next statement i.e.  print("Rolling the dices...") in this case will come after 1 tab.

**while roll_again == "yes" or roll_again == "y":**

 
If you are using Python version 2 then remove the parentheses after print.

   ** print("Rolling the dices...")**
    **print("The values are....")**
    **print(random.randint(min, max))**
    **print(random.randint(min, max))**

If you are using Python2 then use raw_input instead of input method. 
Python also has a feature which lets you interact with the outside world to get input. The raw_input() function waits for the user to type some input and press return. It then gets whatever was typed.

   ** roll_again = input("Roll the dices again?")**
