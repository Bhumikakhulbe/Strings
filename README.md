Table printer: 
A tabulate module is imported from tabulate library and a function printTable() is defined. 
The number of lists and the length of each lists of the list is asked from the user and the input is validated.
An empty list is created (List1) and for loop will run till the entered number of lists.
Inside the loop another list is created (List2) and another for loop is given which will run till the provided length of the list.
The string values of list2 is asked from the user and appended in the List2. 
Once the inside loop ends, List1 will be appended and the outside loop will run and List2 will again be empty.
Then the List1 will be printed in a tabulated format with all the values right justified.
The function is called.

Pig-Latin program: 
A string is taken as an input from the user and the input is validated.
An empty string (string1) is created. The entered string is broken into substrings and the for loop will run for all these substrings.
If the substring is a numeric value, the string1 will be concatenated with the same value.
If the substring is a vowel, The word 'yay' is added behind the substring.
If the substring is a consonant or a consonant cluster, the consonant or the cluster will move to the end of the word followed by 'ay'.
The upper and lower cases will also be checked in this program.
The final string will be printed
