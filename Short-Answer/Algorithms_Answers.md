#### Please add your answers to the ***Analysis of  Algorithms*** exercises here.

## Exercise I

a) This code runs as long as a is less than n cubed, and a increases by n squared each run. So this means there is just the singular input n,
and the runtime will increase proportionally to the size of n. So this would be linear O(n)


b) This is a nested while loop inside of a for loop. The outside for loop would be O(n), as it increases proportional to size of n. Now we also
factor in the nested while loop, which runs as long as j < n, and j will be increasing faster as it is doubled every loop, which represents
a log relationship. The full runtime is O(nlog(n))


c) This is a recursive method, but this function is basic enough that we can just plug and chug and look at the relationship. If we gave arguments of 0, 1, 2, 3, 4 hypothetically, we would receive 0, 2, 4, 6, 8 which is clearly another linear relationship: each time n goes up, the output goes up at the same rate. so O(n)

## Exercise II
As a first pass solution, the obvious answer is to start at the top, and manually check if egg doesnt break from this floor. Keep trying with top floor-1 until we find the exact floor where the egg doesnt break. This is obviously the most basic scenario and would be O(n), as runtime has linear relationship with n. 

