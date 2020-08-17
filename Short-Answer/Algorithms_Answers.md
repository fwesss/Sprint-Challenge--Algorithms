#### Please add your answers to the ***Analysis of  Algorithms*** exercises here.

## Exercise I

a) O(n^3)


b) O(n^2)


c) O(n)

## Exercise II

1) Start from the floor between the highest and lowest floor
2) Throw egg
3a) If egg breaks: 
    1) Note that this is the highest floor checked
3b) If egg doesn't break:
    1) Note that this is the highest floor an egg could survive from so far
    2) Note that this is the lowest floor checked
    
4) Repeat all steps until last floor    

Time complexity: O(log n)
