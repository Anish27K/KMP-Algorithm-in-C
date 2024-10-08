# KMP-Algorithm-in-C
This repository contains a simple C program to implement KMP algorithm for pattern matching.
Instead of using for loops in lps function, if-else statements are used to make the program easy to understand and implement. 

To understand this program, we first want to understand what an lps is : 
LPS stands for longest prefix that is also a suffix.
The purpose of the LPS array is to allow the KMP algorithm to avoid redundant comparisons by "shifting" the pattern intelligently when a mismatch occurs during the search.

The LPS (Longest Prefix Suffix) array for the KMP algorithm is calculated by iterating through the pattern, for each position finding the length of the longest proper prefix which is also a suffix, and updating it using the values from previous LPS entries.

![image](https://github.com/user-attachments/assets/82c689f8-a4b7-47b7-9955-6f029b439302)

After finding the longest prefix that is also a suffix, we write the kmp algorithm for pattern matching. 

