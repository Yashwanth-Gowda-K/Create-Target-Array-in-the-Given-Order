# Create-Target-Array-in-the-Given-Order


## Problem Description
Given two integer arrays `nums` and `index`, construct a target array by inserting each element `nums[i]` at the position `index[i]` in the target array, starting from an empty array.

### Example

Input: nums = [0,1,2,3,4], index = [0,1,2,2,1]
Output: [0,4,1,3,2]
Solution Approach
Initialization: Start with an empty target array
Iterative Insertion: For each pair (nums[i], index[i]), insert the number at the specified position
Result Construction: Build the array incrementally according to the insertion rules

Key Features
Simple Implementation: Uses basic list operations
Handles Edge Cases: Empty inputs, duplicate indices
Time Complexity: O(n²) worst-case due to list insert operations
Space Complexity: O(n) for the target array storage
