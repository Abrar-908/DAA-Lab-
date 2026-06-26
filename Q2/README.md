Title

Program to Count Common Elements Between Two Arrays

Aim

To write a Python program that calculates:

answer1: the number of indices i such that nums1[i] exists in nums2.
answer2: the number of indices i such that nums2[i] exists in nums1.

The program returns the result as [answer1, answer2].

Algorithm
Start.
Read the sizes n and m of the two arrays.
Input the elements of nums1 and nums2.
Convert nums1 and nums2 into sets for efficient lookup.
Initialize answer1 = 0.
Traverse each element in nums1:
If the element exists in nums2, increment answer1.
Initialize answer2 = 0.
Traverse each element in nums2:
If the element exists in nums1, increment answer2.
Return [answer1, answer2].
Stop.

Time Complexity

Let:

n = size of nums1
m = size of nums2

Creating sets takes O(n + m) time.

Checking membership for each element takes O(1) on average.

Therefore,

Time Complexity = O(n + m)

Space Complexity

Two sets are used to store elements of both arrays.

Space Complexity = O(n + m)

Result

The Python program was successfully implemented to count the number of elements in each array that also exist in the other array. The program efficiently uses sets to achieve linear time complexity and correctly returns the result in the form [answer1, answer2].
