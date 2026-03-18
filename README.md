# two-sum-problem
A simple and efficient solution to the Two Sum problem, where the goal is to find two numbers in an array that add up to a given target value. This project demonstrates the use of hashing for optimal performance.
# 🔍 Two Sum Problem

This project solves the classic **Two Sum** problem using an efficient approach with hashing.

## 🧠 Problem Statement
Given an array of integers and a target value, return the indices of the two numbers such that they add up to the target.

## 🚀 Approach
- Use an unordered_map to store visited elements
- For each element, check if the complement exists
- Return indices if found

## 💻 Technologies Used
- C++

## ▶️ How to Run
1. Clone the repository
2. Compile using:
   g++ two_sum.cpp
3. Run:
   ./a.out

## 📈 Complexity
- Time: O(n)
- Space: O(n)

## 📌 Example
Input:
nums = [2,7,11,15], target = 9

Output:
[0,1]
