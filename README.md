# Minimum Increment to Make Array Unique

LeetCode Q # 945.

You are given an integer array nums. In one move, you can pick an index i where 0 <= i < nums.length and increment nums[i] by 1.

Return the minimum number of moves to make every value in nums unique.

The test cases are generated so that the answer fits in a 32-bit integer.

Example 1:

>Input: nums = [1,2,2]</br>
>Output: 1</br>
>Explanation: After 1 move, the array could be [1, 2, 3].

Example 2:

>Input: nums = [3,2,1,2,1,7]</br>
>Output: 6</br>
>Explanation: After 6 moves, the array could be [3, 4, 1, 2, 5, 7].</br>
>It can be shown with 5 or less moves that it is impossible for the array to have all unique values.

My Solution Analysis:

<div align = "center">

  ![image](https://github.com/xo-azeem/Minimum-Increment-to-Make-Array-Unique-LeetCode/assets/171427226/869d3455-9d0f-4141-8b52-8a051fb52732)

  Time complexity: O(n log n).</br>Space complexity: O(1).
</div>
