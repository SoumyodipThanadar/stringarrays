1. Given two numbers, the task is to find the number of carry operations required when two numbers are added as below.
Example:
Input:
A1234, B=567
Output: 2

2. Given an unsorted array arr[] of size n, the task is to find the minimum difference between any pair in the given array.
Input: arr[] = {1, 2, 3, 4} Output: 1
Input: arr[] = {10, 2, 5, 8} Output: 2

3. Given an array sequence [A1, A2 ...A], the task is to find the maximum possible sum of increasing subsequence S of length k such that S₁<=S,<=S...<=S.
Example
Input:
n=9k=4
A=[2 5 3 9 15 33 6 18 20]
Output: 62
Possible Increasing subsequence of Length 4 with maximum possible sum is 9 15 18 20
Example
Input:
n=9k=4
A=[2 5 3 9 15 33 6 18 20]
Output: 62
Possible Increasing subsequence of Length 4 with maximum possible sum is 9 15 18 20

4. Given an array arr of size N and an integer K. The task is to find the pair of integers such that their sum is maximum and but less than K
Example:
Input: arr = {5, 20, 110, 100, 10}, K = 100
Output: 20, 10


5. Given an array arr of size N and an integer K. The task is to find the integers that is nearest to K
Example:
Input: arr = {5, 20, -4, 12, -3}, K=0 Output: -3
Input: arr = {15, 20, -4, 12, -3}, K=17 Output: 20

6. Given an unsorted array with both positive and negative elements including 0. The task is to find the smallest positive number missing from the array in O(N) time.
Examples:
Input: arr[] = {-5, 2, 0, -1, -10, 15}
Output: 1
Input: arr = {1, 1, 1, 0, -1, -2}
Output: 2

7. Given an input string, write a program to find the frequency of letters in a string in O(n) time (Run Length Encoding).
Examples:
Input: aaabbcc
Output: 3a2b2c

8. ARTO(Regional Transport Office) issues vehicle's registration number. Given a vehicle's registration number task is to find number of vehicles already registered before the given vehicle in that RTO. The format of a vehicle number is as follows:
SS-RR[P*]-NNNN
where SS is state code, RR is RTO code, P* is zero or one character of the sequence in the RTO, NNNN is four character long number. Assume that first vehicle in a state 'SS' and RTO code 'RR' is SS-RR-0000,
Example:
Input: WB-25-0010

Output: 10
Input: WB-25A-0010 Output: 10010
Input: WB-258-0010
Output: 20010


