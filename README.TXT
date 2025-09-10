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
10. the error message says: Error: non-static method getValue() cannot be referenced from a static context
the error happened because the get method used the class NumberDisplay, instead of the variable, digit, which actually 
stores the value
11. the error message says: Error: '.class' expected
this happened because the parameter (int 5) shouldn't have int in it.
12. if((replacementValue >= 0) && (replacementValue <= limit)) was modified. now that there's a <=, getting the value will 
10, even if the rollover limit is 10 (which would normally reset the return number to 0
13. x
14. the parameters can now use negative numbers or numbers past the limit since only one condition needs to be true
(getValue() will return 7 even if the rolloverLimit is 6 for example)
15. (! in an expression means the opposite of what the expression says)
!(4<5) returns false because 4<5 is true, but the ! isn't
!false returns true because the opposite of false is true
(2 > 2)||((4 == 4) && (1 < 0)) returns false because 2>2 isn't true and ((4 == 4) && (1 < 0)) returns false since both must be true (1<0 is false)
(2 > 2)||(4 == 4) && (1 < 0) returns false because 2>2 and 1<0 are not true
(34 != 33) && !false returns true because != means not equal (34 and 33 aren't the same) and !false means true

16. (a && b)||(!a && !b)
17. (a && !b)||(!a && b) (exclusive or)
18. if i input a number higher than 3 digits, getValue will just return "00", a two digit number, but if if i setValue to 100 from 1000, getValue 
will return 100 (a three digit number)