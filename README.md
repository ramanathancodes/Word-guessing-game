In this game, there is a list of words present, out of which our interpreter will choose 1 random word. The user first has to input their names and then, will be asked to guess any alphabet. If the random word contains that alphabet, it will be shown as the output(with correct placement) else the program will ask you to guess another alphabet. The user will be given 12 turns(which can be changed accordingly) to guess the complete word.


++++++++++++++++++++++
Output
+++++++++++++++++++++++




What is your name? Gautam
Good Luck!  Gautam
Guess the characters
_
_
_
_
_
guess a character:g
g
_
_
_
_
guess a character:e
g
e
e
_
_
guess a character:k
g
e
e
k
_
guess a character:s
g
e
e
k
s
You Win
The word is:  geeks 



+++++++++++++++++++++
End of OutPut
+++++++++++++++++++



Algorithm :

Needed input : Name 
Needed Variables : A list containing 5 letter english words  , Number of guesses , random_word 
logic : 

1. Get Name 
2. Greet back 
3. Initialise random word 
4. number of guesses 
5. have a while loop for repeating guess till number of guesses 
6. Print 5 lines dashes or filled output at end of guesses 
7. Break the loop is guess is correct 
8. add while-else for max number guesses expired message 


