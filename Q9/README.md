Title

Binary Search to Find an Element in an Array

Aim

To search for a given key in a sorted array using the Binary Search technique.

Algorithm
Sort the array.
Set low = 0 and high = n - 1.
Find the middle element.
If the middle element equals the key, return its position.
If the key is smaller, search the left half.
Otherwise, search the right half.
Repeat until the element is found or the search space becomes empty.

Time Complexity
Sorting: O(n log n)
Binary Search: O(log n)

Overall Time Complexity: O(n log n)

Space Complexity

O(1)

Result

The program successfully searches for an element using Binary Search after sorting the array.
