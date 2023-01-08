# Workshop: The basics of python 


Python is an interpreted, cross-paradigm, cross-platform programming language. It promotes structured, functional and object-oriented imperative programming. 


 # Part 1 : Introduction
 
   ## Task 00 -HelloWord :
    Let's start with a good old “Hello world” program, first of all, create a new file callde ‘hello_world.py’.
    To print something on the console you just need to call the print() function. 
    When you are done writing your code, launch your programm using python3: 
    
   ![Cover](https://github.com/leDarron/Workshop_Python_Basics/blob/main/images/helloworld.png)
   ##
    
   ## Task 01 -Variables :
    In python, variables are non-typed, you can asign any value of any type to any variables.
    You can also change the type of a variable as you wish. 
    The print() function takes as many parameters as you want of the type you want.
    You should try create some variables and print them
     
   ![Cover](https://github.com/leDarron/Workshop_Python_Basics/blob/main/images/task01.png)
   ##

   ## Task 02 -Tupples :
      Tuples are used to store multiple items in a single variable. You can put as many item as you want in a tuple.
      Here is the syntax: 
      
   ![Cover](https://github.com/leDarron/Workshop_Python_Basics/blob/main/images/tuples.png)
   
     Try to get your tupple's values and print them.
   ##     
   
   ## Task 03 -list :
      Just as tuples, lists are used to store multiple items in a single variable, but it allow you to add and remove items. 
      To add or remove items of your list, use the function append() and remove().
      Try to get your list and print them.
      
   ![Cover](https://github.com/leDarron/Workshop_Python_Basics/blob/main/images/task03.png)
   ##
   
   ## Task 04 -Dictionaries :
     A dictionary is a collection of key-value pairs, it allows you to bind a value to a key. 
     Here is the syntax: 
     
   ![Cover](https://github.com/leDarron/Workshop_Python_Basics/blob/main/images/task04.png)
   
    Create a dictionary and associate the string "name" to the string "epitech" and the the string "price" to the number 10000 
   ##
   
   ## Task 05 -Conditions_nd_loops :
     After a condition (if/elif/else) or a loop (while/for), you must put a ‘:’ 
     then all the code you want to be within the condition must be correctly indented. 
     
   ![Cover](https://github.com/leDarron/Workshop_Python_Basics/blob/main/images/conditions.png)
     
     Now try to write a program that print all the odd numbers between 0 and 20 
   ##
 
   ## Task 06 -Functions :
    In Python, a function is defined using the def keyword 
    
   ![Cover](https://github.com/leDarron/Workshop_Python_Basics/blob/main/images/function.png)
   
    Now try to create the following functions: 
         - add(n1, n2), it returns n1 + n2 
         - odds(n) it prints all the odd numbers between 0 and n 
         - letters(c) it prints the alphabet starting from c 
         
   ##
   
   ## Task 07 -Vectorial_Calculation :
     Write a function that takes a list of vectors (tuples) and returns the addition of all vectors of the list. 
     (a1 ,b1 )+(a2 ,b2 )=(a1 +a2 ,b1 +b2 ) 
  ##
  
  # Part 2: Final Project
  
   ## Task 08 -TIc Tac Toe:
    Board :
       First, create a function that initializes the board. The board is a 3x3 array filled with ‘ ‘ at the beginning.
       Then write a function that prints this board. 

    Player's move :
       Write a function called ‘player_move’ that takes 3 parameters: x, y, player and put a ‘X’ or a ‘O’ (depending on the parameter player) at x,y 
       int the array. This function should return 0 if the move is possible, otherwise, 1. 

    Game loop :
       Write an infinite loop and read the input (the player must write the coordinates of his move) of the players 
       then call your function player_move with the given coordinates.
    
    Win or lose :
      write a function that return 1 if the player X won, 2 if the player O won, 3 it is a tie and 0 if the game is not over yet.
      After each move, check if the game is over, if it is, you should print something to inform the players that the game is over and who is the winner. 
    
   
