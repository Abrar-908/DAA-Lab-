Title

Program to Count Equal and Divisible Index Pairs in an Array

Aim

To write a Python program that counts the number of pairs (i, j) such that:

0 ≤ i < j < n
nums[i] == nums[j]
(i × j) is divisible by k
Algorithm
Start.
Read the size n of the array.
Input the elements of the array nums.
Read the integer k.
Initialize count = 0.
Traverse all possible pairs (i, j) where i < j:
Check whether nums[i] == nums[j].
Check whether (i * j) % k == 0.
If both conditions are true, increment count.
Print the value of count.
Stop.

Time Complexity

Let n be the number of elements in the array.

Two nested loops examine every possible pair.
Time Complexity=O(n
2
)
Space Complexity

The algorithm uses only a few extra variables (count, i, j).

Space Complexity=O(1)
Result

The Python program was successfully implemented to count all pairs (i, j) such that the elements at those indices are equal and the product of their indices is divisible by k. The program correctly produces the required output for the given examples.
