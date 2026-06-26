Title

Maximum Money Robbed from Circular Houses

Aim

To determine the maximum amount of money that can be robbed from houses arranged in a circle without robbing two adjacent houses.

Algorithm
If there is only one house, return its value.
Solve two cases:
Rob houses from 0 to n-2.
Rob houses from 1 to n-1.
For each case, use dynamic programming:
dp[i] = max(dp[i-1], dp[i-2] + nums[i])
Return the maximum of the two cases.

Time Complexity

O(n)

Space Complexity

O(1)

Result

The program successfully finds the maximum amount that can be robbed from circularly arranged houses using dynamic programming while ensuring that no two adjacent houses are robbed.
