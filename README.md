# Valleys-and-Hills

Problem Code: VANDH

Chef built a binary string S that has exactly N hills and M valleys.

A hill is any index 1<i<|S| such that both its neighbors are strictly smaller than it, i.e, Si−1<Si and Si+1<Si.

A valley is any index 1<i<|S| such that both its neighbors are strictly larger than it, i.e, Si−1>Si and Si+1>Si.

Chef thinks that his string S is the shortest among all binary strings with N hills and M valleys. You don't quite trust his words, so to verify his claim you would like to find the shortest binary string with exactly N hills and M valleys.

If there are multiple possible binary strings of the least length satisfying the given condition, you may print any of them.

Input Format
The first line of input will contain a single integer T, denoting the number of test cases. The description of T test cases follows.
The first and only line of each test case contains two space-separated integers N and M, the required number of hills and valleys respectively.

Output Format
For each test case, output two lines.
  1. The first line contains the length of the binary string you constructed to satisfy the given conditions.
  2. The second line contains the string itself.

Constraints
1≤T≤2500
1≤N≤500
1≤M≤500
The sum of lengths of the answer strings across all test cases does not exceed 2⋅105

Subtasks
Subtask 1 (10 points):

1≤N≤50
1≤M≤50

You may output any string of length not exceeding 320 containing exactly N hills and M valleys: it need not be shortest by length. It is guaranteed that at least one such string with length ≤320 exists.
Subtask 2 (90 points):

Original constraints
The binary string you construct must be shortest by length.

Sample Input 1 
3
3 2
2 3
3 3

Sample Output 1 
7
0101010
7
1010101
8
01010101
