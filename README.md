# Partition Equal Subset Sum (LeetCode 416)

This repository contains a Python solution to the classic **"Partition Equal Subset Sum"** problem from LeetCode, solved using an optimized **Dynamic Programming** approach.

## 🧠 Problem Statement

Given a non-empty array `nums` containing only positive integers, determine if the array can be partitioned into two subsets such that the sum of elements in both subsets is equal.

### Example 1
#### Input: nums = [1, 5, 11, 5] 
#### Output: true 
#### Explanation: The array can be partitioned as [1, 5, 5] and [11].

### Example 2
#### Input: nums = [1, 2, 3, 5] 
#### Output: false

## ✅ Solution Approach

- Calculate the **total sum** of all elements.
- If the sum is **odd**, return `False` (can't split into two equal subsets).
- If even, check if there's a **subset with sum = total // 2** using **1D Dynamic Programming**.
- Time Complexity: `O(n * sum)`
- Space Complexity: `O(sum)`
  
## 🌟 Star This Repo
Feel free to star ⭐ the repo and share with others if you find this helpful.


