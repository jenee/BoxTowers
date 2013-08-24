Solving InterviewStreet Problem: Box Towers

From: https://box.interviewstreet.com/challenges/dashboard/#problem/4f3c491b4a54c


Okay, we have a max of 20 blocks.
- there are 20! different ways that these blocks can be arranged
 - 20! = 2432902008176640000
- each block has three dimensions: L, W, H
 - therefore, there are 3!, or 6, ways that each block can be rotated
- 20! * 6! = 1751689445887180800000 aka A LOT

So, we have to figure out a way to narrow down the possibilities.


Possible Approach 1:
   1-Organize the blocks so that the longest dimension is the height.
   2-See if they stack that way.

Rotation strategy:

make it so that 2x4 and 4x2 will stack on top of eachother.






