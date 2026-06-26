Title

Program to Find the First Palindromic String in an Array

Aim

To write a Python program that finds and returns the first palindromic string from a given array of strings. If no palindrome exists, the program returns an empty string ("").

Algorithm
Start.
Read the number of words n.
Input n strings into a list words.
Traverse each word in the list:
Reverse the word.
Compare the original word with its reversed version.
If both are equal, print the word and terminate the search.
If no palindrome is found after checking all words, print an empty string ("").
Stop.

Time Complexity
Let n be the number of strings and m be the maximum length of a string.
Reversing and comparing a string takes O(m) time.
In the worst case, all strings are checked.

Time Complexity = O(n × m)

Space Complexity
The slicing operation word[::-1] creates a reversed copy of the string of length m.

Space Complexity = O(m)

(If a two-pointer approach is used, it can be reduced to O(1) auxiliary space.)

Result

The Python program was successfully implemented to identify and return the first palindromic string in an array of words. If no palindromic string exists, the program correctly returns an empty string ("").

