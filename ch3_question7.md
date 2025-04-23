## Problem
How many positive integers less than 850 are multiples of 9,5, or 2? Use the principle of Inclusion/Exclusion.

## Solution

First we should define the sets we are looking for. 
Let:
A be the set of multiples of 9
B be the set of multiples of 5
C be the set of multiples of 2

|A∪B∪C| = |A|+|B|+|C|-|A∩B|-|A∩C|-|B∩C|+|A∩B∩C|

The reasoning for this is that we want to include all the numbers in the set of A, B and C. However we don't want to include a number twice so we remove all numbers that are in two sets. Then we add back the numbers that are in all three sets because those numbers were removed from the count twice so we need to include them back in. This formula is known as the Principle of Inclusion/Exclusion or simply PIE

|A| = 849/9 = 94
|B| = 849/5 = 169
|C| = 849/2 = 424

|A∩B| = 849/(9*5) = 18
|A∩C| = 849/(9*2) = 47
|B∩C| = 849/(5*2) = 84

|A∩B∩C| = 849/(9*5*2) = 9

|A∪B∪C| = 94+169+424-18-47-84+9 = 547

This shows that the final answer is 547 because of the Principle of Inclusion/Exclusion

