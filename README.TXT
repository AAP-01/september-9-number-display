Project: number-display
Authors: Michael Kölling and David J. Barnes

This project is part of the material for the book

   Objects First with Java - A Practical Introduction using BlueJ
   Seventh edition
   David J. Barnes and Michael Kölling

It is discussed in chapter 3.

To use this project, create an instance of class NumberDisplay. Then inspect this 
instance and leave the inspector window open. With the inspector window open, 
call the object's methods, such as increment and setValue.

Lab 3

1. x
2. x
3. x
4. x
5. the private in value goes back to 0 after calling the increment method 24 times
6. NumberDisplay hours = new NumberDisplay(24);
   NumberDisplay minutes = new NumberDisplay(60);
7. display.getValue() doesn't use ; since it isn't a statement, unlike display.increment();
8. the maximum number for the display variable is 6. if i set the value to 5 and 
get it, the terminal will return 5. if i set the value to above 6 and get it, the terminal 
will still show 5 because 10 is above the maximum (6)
9. for the digit variable, the rollover limit (maximum number) is 10. if i setValue to 10 and get 
it, the terminal will return 0 because the value hit the limit and reset
10. 