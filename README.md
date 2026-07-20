# Longest Valid Parentheses

## Problem
Given a string containing only '(' and ')', find the length of the longest valid (well-formed) parentheses substring.

## Solution
This solution uses a stack to store indices of parentheses.

### Time Complexity
O(n)

### Space Complexity
O(n)

## Sample Test Cases
Input:
(() 
Output:
2

Input:
)()())
Output:
4

Input:
""
Output:
0
