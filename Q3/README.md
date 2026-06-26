Title

Program to Find the Sum of Squares of Distinct Counts of All Subarrays

Aim

To write a Python program that computes the sum of the squares of the distinct counts of all possible contiguous subarrays of a given integer array.

Algorithm
Start.
Read the size n of the array.
Input the elements of the array nums.
Initialize total_sum = 0.
For each starting index i from 0 to n-1:
Create an empty set distinct_elements.
For each ending index j from i to n-1:
Insert nums[j] into the set.
Compute the number of distinct elements as len(distinct_elements).
Add the square of this value to total_sum.
Print total_sum.
Stop.

Time Complexity

Let n be the number of elements in the array.

The outer loop runs n times.
The inner loop runs up to n times.
Set insertion and lookup operations take O(1) on average.

Therefore,

Time Complexity = O(n²)

Space Complexity
A set is used to store distinct elements in the current subarray.
In the worst case, it may contain all n elements.

Space Complexity = O(n)

Result

The Python program was successfully implemented to calculate the sum of the squares of distinct counts for all possible subarrays of an integer array. The algorithm correctly handles duplicate elements and produces the expected output for the given examples.
