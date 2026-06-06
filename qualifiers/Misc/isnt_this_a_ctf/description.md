Challenge Title: `isnt_this_a_ctf`<br>
Author: `nmluan`<br>

Description:<br>
Each sensor array beamed down from the orbital station should arrive sorted,
but cosmic interference scrambles the values. The team measures "disorder" as
the number of inversions: pairs (i, j) where i < j but a[i] > a[j].<br>

Given T test cases, print the inversion count for each array.<br>
Sum all answers together and wrap the result as the flag.<br>

Constraints:<br>
  1 ≤ T ≤ 1000<br>
  200 ≤ N ≤ 10,000<br>
  1 ≤ a[i] ≤ 10^9<br>
  All values within a test case are distinct.<br>

Input format:<br>
  First line: T<br>
  For each test case:<br>
    Line 1: N<br>
    Line 2: N space-separated integers<br>

Output format:<br>
  For each test case, one line containing the inversion count.<br>

Sample input:<br>
  3<br>
  4<br>
  3 1 2 4<br>
  5<br>
  5 4 3 2 1<br>
  5<br>
  1 2 3 4 5<br>

Sample output:<br>
  2<br>
  10<br>
  0<br>

Distributed files: input.txt<br>
Flag format: ASRCTF{[sum of all answers]}