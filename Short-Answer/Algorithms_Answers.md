Add your answers to the Algorithms exercises here.


A.) 0(n)



B.) This algorithm has a cubic running time: O(n^3).
- because of the triple nested loops

C.) 0(n)

## Exercise II

`Suppose that you have an _n_-story building and plenty of eggs. Suppose also that an egg gets broken if it is thrown off floor _f_ or higher, and doesn't get broken if dropped off a floor less than floor _f_. Devise a strategy to determine the value of _f_ such that the number of dropped eggs is minimized.

Write out your proposed algorithm in plain English or pseudocode and give the runtime complexity of your solution.`

  
  Step 1: Go to the middle floor _f_ and throw an egg, 
   If egg is broken,
   all of the floors above can be eliminated. 
   else If it is not broken,
    all of the floors below can be eliminated 
  Step 2: Go to the middle floor of the remaining floors and repeat step 1