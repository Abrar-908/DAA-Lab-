Title

Program to Create a List of Unique Elements

Aim

To create a new list containing only the unique elements from the given list of numbers.

Algorithm
Create an empty set seen and an empty list unique_list.
Traverse each element in the input list.
If the element is not in seen, add it to both seen and unique_list.
Return unique_list.

Time Complexity

O(n)

(Each element is processed once, and set operations take O(1) on average.)

Space Complexity

O(n)

(An additional set and list may store up to n unique elements.)

Result

The program successfully creates a new list containing only unique elements while preserving their original order. The algorithm runs in O(n) time and requires O(n) extra space.
