# -Pangrammatic-window-javascript
According to the dictionary is a statement that contains all the alphabetical letters.

This code was submitted as a assignment given by Professor Edwin Brady at University of Saint Andrews under the course module of CS5002


The program will work on the following steps:-
● The phrase is taken as input from the user.
● An array of length 26 is counted with 0 to all indexes.
● Since keeping character as 0 to 65 make it more tricky. We can use the idea of ascii
unique code or unicode.
● As, each character of the phrase is iterated. They're being treated as follows:
For A (65) -> 65 - 65 = 0th value of the array is converted to 1
For D (68) -> 68 - 65 = 3rd value of the array is converted to 1
For c (99) -> 99 - 97 = 2nd value of the array is converted to 1
For y (121) -> 121 - 97 = 24th value of the array is converted to 1
etc.
● After the iteration is completed, if 1 is found in all indexes of the array the phrase is said
to be "pangrammatic" otherwise not.


This algorithm is submitted by Shivang Sinha.
