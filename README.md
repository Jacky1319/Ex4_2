# Ex4_2
## What is a binary search?
Binary search is a way for seraching the location of a given number in an array.
## How a binary search works?
1. We assume that the element of the array have been sorted and the given number is in the array.
2. Compare the given number with the middle number in the array, if it matches, the searching is over.
3. If the middle number is smaller than the given number, regard the numbers behind middle number as a new array, then use step 2 again.      If the middle number is larger than the given number, regard the numbers before middle number as a new array, then use step 2 again.
