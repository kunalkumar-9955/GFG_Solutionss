# Longest Bitonic Subarray

| Property | Value |
|----------|-------|
| **Difficulty** | Unknown |
| **Language** | Java (21) |
| **Solved On** | July 15, 2026 |
| **Problem Link** | [View on GeeksforGeeks](https://www.geeksforgeeks.org/problems/maximum-length-bitonic-subarray5730/1) |

## Problem Summary

Given an array arr[] containing positive integers, return the maximum length of the bitonic subarray.
A subarray arr[i...j] is considered bitonic if its elements first monotonically increase, and then monotonically decrease. Formally, there exists an index k (where i <= k <= j) such that:

arr[i] <= arr[i+1] <= . . . <= arr[k] 
arr[k] >= arr[k+1] >= . . . >= arr[j]

Examples: 
Input: arr[] = [12, 4, 78, 90, 45, 23]
Output: 5
Explanation: The longest bitonic subarray is [4, 78, 90, 45, 23], it…

## Solution

See the solution file in this directory.

---
*Auto-synced by [GFGHub](https://github.com/your-repo/gfg-hub) Chrome Extension*
