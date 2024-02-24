# Recursion
Recursion

//Easy level : question 1

Problem Statement: Print 1 To N Without Loop

Given:
Print numbers from 1 to N without the help of loops.

Problem Link: https://www.geeksforgeeks.org/problems/print-1-to-n-without-using-loops-1587115620/1

Note: for code check attached file with name Print 1 To N Without Loop


//Easy level : question 2
Problem Statement: Pascal Triangle

Given:
Given a positive integer N, return the Nth row of pascal's triangle.
Pascal's triangle is a triangular array of the binomial coefficients formed by summing up the elements of previous row.
The elements can be large so return it modulo 109 + 7.

Example 1:
Input:
N = 4
Output: 
1 3 3 1
Explanation: 
4th row of pascal's triangle is 1 3 3 1.

Example 2:
Input:
N = 5
Output: 
1 4 6 4 1
Explanation: 
5th row of pascal's triangle is 1 4 6 4 1.

Your Task:
Complete the function nthRowOfPascalTriangle() which takes n, as input parameters and returns an array representing the answer. 
You don't to print answer or take inputs.

Expected Time Complexity: O(N2)
Expected Auxiliary Space: O(N2)

Constraints:
1 ≤ N ≤ 103

Problem Link: https://www.geeksforgeeks.org/problems/pascal-triangle0652/1?page=1
Note: for code check attached file with name Pascal Triangle

//Easy level : question 3

Problem Statement: Fibonacci series up to Nth term

Given:
You are given an integer n, return the fibonacci series till the nth(0-based indexing) term. Since the terms can become very large return the terms modulo 109+7.

Example 1:
Input:
n = 5
Output:
0 1 1 2 3 5
Explanation:
0 1 1 2 3 5 is the Fibonacci series up to the 5th term.

Example 2:
Input:
n = 10
Output:
0 1 1 2 3 5 8 13 21 34 55
Explanation:
0 1 1 2 3 5 8 13 21 34 55 is the Fibonacci series up to the 10th term.

Your Task:
You don't need to read input or print anything. Your task is to complete the function Series() which takes an Integer n as input and returns 
a Fibonacci series up to the nth term.

Expected Time Complexity: O(n)
Expected Space Complexity: O(n)

Constraint:
1 <= n <= 105

Problem Link: https://www.geeksforgeeks.org/problems/fibonacci-series-up-to-nth-term/1

Note: for code check attached file with name Fibonacci series up to Nth term


//Easy level : question 4

Problem Statement: Insertion Sort

Given:
The task is to complete the insert() function which is used to implement Insertion Sort.


Example 1:
Input:
N = 5
arr[] = { 4, 1, 3, 9, 7}
Output:
1 3 4 7 9

Problem Link: https://www.geeksforgeeks.org/problems/insertion-sort/1

Note: for code check attached file with name Insertion Sort

//Easy level : question 5

Problem Statement: Bubble Sort

Given:
Given an Integer N and a list arr. Sort the array using bubble sort algorithm.

Example 1:
Input: 
N = 5
arr[] = {4, 1, 3, 9, 7}
Output: 
1 3 4 7 9

Problem Link: https://www.geeksforgeeks.org/problems/bubble-sort/1

Note: for code check attached file with name Bubble Sort



//Easy level : question 6

Problem Statement: Selection Sort

Given:
Given an unsorted array of size N, use selection sort to sort arr[] in increasing order.

Example 1:
Input:
N = 5
arr[] = {4, 1, 3, 9, 7}
Output:
1 3 4 7 9

Explanation:
Maintain sorted (in bold) and unsorted subarrays.
Select 1. Array becomes 1 4 3 9 7.
Select 3. Array becomes 1 3 4 9 7.
Select 4. Array becomes 1 3 4 9 7.
Select 7. Array becomes 1 3 4 7 9.
Select 9. Array becomes 1 3 4 7 9.

Problem Link: https://www.geeksforgeeks.org/problems/selection-sort/1?utm_source=geeksforgeeks&utm_medium=article_practice_tab&utm_campaign=article_practice_tab

Note: for code check attached file with name Selection Sort

//Medium level : question 1

Problem Statement: Merge Sort

Given:
Given an array arr[], its starting position l and its ending position r. Sort the array using merge sort algorithm.

Example 1:
Input:
N = 5
arr[] = {4 1 3 9 7}
Output:
1 3 4 7 9

Your Task:
You don't need to take the input or print anything. Your task is to complete the function merge() which takes arr[], l, m, r as its input parameters and
modifies arr[] in-place such that it is sorted from position l to position r, and function mergeSort() which uses merge() to sort the array in ascending
order using merge sort algorithm.

Expected Time Complexity: O(nlogn) 
Expected Auxiliary Space: O(n)

Constraints:
1 <= N <= 105
1 <= arr[i] <= 105

Problem Link: https://www.geeksforgeeks.org/problems/merge-sort/1

Note: for code check attached file with name Merge Sort

