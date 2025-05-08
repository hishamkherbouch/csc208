#3.5 Question 6

After gym class you are tasked with putting the 21 identical dodgeballs away into 10 bins.
a. How many ways can you do this if there are no restrictions?
b. How many ways can you do this if each bin must contain at least one dodgeball?


A. This is a stars and bars problem where you have n number of dodgeballs and k number of bins. 
In this case n=21 and k=10. 
The formula to solve this is 
$$\binom{n + k - 1}{k-1}$$
$$\binom{30}{9}$$
This comes out to 14307150.

B. For this problem you have to do almost the same thing but first subtract 10 balls because you place at least one into each bin.
Now you can use the same formula but n=11 instead of 21.
$$\binom{20}{9}$$
This comes out to 167960