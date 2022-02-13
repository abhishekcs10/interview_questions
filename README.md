# interview_questions
Interview questions asked in different companies

# Google 

## Telephonic Round
1- Given n numbers find the longest increasing subsequence given that the difference between consecutive numbers in subsequence is less than or equal to d;

Sol:  i Brute force of LIS by adding condition
ii. O(n\*d) solution using map which was accepted

## Onsite Rounds

1. given nx3 floor, find number of ways of tiling floor using 1x3 & 2x3 tiles.
2. Given mxn matrix, with each cell marked as whether there is a lion present on that cell or not. Find the minimum distance that you can maintain while moving from src cordinate to destination cordinate in the matrix
3. Given mxn matrix filled with integers, find row wise maximum that can be accumulated while moving from top to bottom given below condition:
  if you selec ith col in row k, and jth col for row k+1, then cost of selecting jth col would be abs(i-j) and total profit counted would be row[k][i]+row[k+1][j]-abs(i-j)
4. Given mxn matrix, which represent heights of towers at each cell. Water can flow from higher tower to lower height tower. You are given two cordinate points where you have to supply water. Find, if exists, cordinate where you should install a tank so that water reaches both the cordinates in minimum time. (Time take is manhattan distance between the coordinates).
