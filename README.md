# Prime-Digit-Replacement
Problem Statement
You are tasked with finding the smallest prime number that can form a family of primes by replacing specified digits with the same digit.

Input Format
The input consists of three integers:

L (1 ≤ L ≤ 10): The number of primes you want in the output family.
D1 (0 ≤ D1 < 5): The index of the first digit to be replaced (0-indexed).
D2 (0 ≤ D2 < 5): The index of the second digit to be replaced (0-indexed).
Output Format
Print the first L numbers of the prime value family found in increasing order, separated by spaces.

Constraints
It is guaranteed that a solution exists.
Leading zeros should not be considered when forming new numbers.
If there are multiple solutions, choose the "lexicographically" smallest one.
Sample Input
5 2 7

Sample Output
56003 56113 56333 56443 56663 56773 56993

Sample Input
2 1 3

Sample Output
11 13 17

Explanation
In the first sample, by replacing the 3rd and 8th digits of certain prime numbers, you can generate a family of at least 5 prime numbers. In the second sample, replacing the specified digits produces a family containing at least 2 prime numbers.
