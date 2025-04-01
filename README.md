# Find-the-Missing-Number-in-a-Sequence
You are given an array of integers from 1 to N with one number missing. Your task is to find the missing number. The array contains N-1 numbers and is in the range from 1 to N.
Explanation:
The approach is the same as the Python solution: we use the formula for the sum of the first N natural numbers:
Sum=𝑁×(𝑁+1)2 
The sum of the numbers in the array is calculated, and the missing number is simply the difference between the expected total sum and the actual sum of the array elements.

Time Complexity:
O(N): The solution requires a single traversal of the array to calculate the sum.

Space Complexity:
O(1): We are using only a few variables to hold the sums and no additional space for data structures.
