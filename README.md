# interview_questions
Interview questions asked in different companies

# Google 

## Telephonic Round
1- Given n numbers find the longest increasing subsequence given that the difference between consecutive numbers in subsequence is less than or equal to d. 
   Given condition: d <<<<< n
   
Sol:  i Brute force of LIS by adding condition
ii. O(n\*d) solution using map which was accepted

## Onsite Rounds

1. given nx3 floor, find number of ways of tiling floor using 1x3 & 2x3 tiles. Tiles can be rotated
2. Given mxn matrix, with each cell marked as whether there is a lion present on that cell or not. Find the minimum distance that you can maintain while moving from src cordinate to destination cordinate in the matrix
3. Given mxn matrix filled with integers, find row wise maximum that can be accumulated while moving from top to bottom given below condition:
  if you selec ith col in row k, and jth col for row k+1, then cost of selecting jth col would be abs(i-j) and total profit counted would be row[k][i]+row[k+1][j]-abs(i-j)
4. Given mxn matrix, which represent heights of towers at each cell. Water can flow from higher tower to lower height tower. You are given two cordinate points where you have to supply water. Find, if exists, cordinate where you should install a tank so that water reaches both the cordinates in minimum time. (Time take is manhattan distance between the coordinates).
5. Given n numbers find the longest increasing subsequence given that the difference between consecutive numbers in subsequence is less than or equal to d;
  No condition on d this time. nlogn solution was required.
6. Given schedule of flights with time when the flights arrive and depart from a location, find if you attend meeting at a destination place at given time starting from source place at given time. Any number of flights could be taken in between.


Result: *Rejected*

Feedbacks:

I was judged on below 5 points mainly as per HR review
1. DS and Algo
2. Time complexity of solution
3. Coding 
4. Code reusability and readability
5. Communication

I was able to solve all the above problem except 6th. Got good rating for 1,2 point. But because of not handling corner cases or copy pasting repeated lines of code, I was marked below average in 3 and 4. Your code has to be perfect to score that. I was confident to be selected as I had solved the problems with time complexities expected from interviewer but was on the verge because of coding part. Although I could have easily corrected those mistakes if pointed but I guess interviewers intention was to check how perfect I can code in one go.

After first 4 questions, I was put on hold rating by hiring committee. An additional interview happened in which Q6 was asked. I had performed bad in that and it was decisive round. I however requested HR to get me an additional round which she did, Q5 was asked in the round which I was able to solve but was rated average because of coding part.

