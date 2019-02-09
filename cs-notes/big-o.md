# Big O notation 

What is Big O notation(“O” stands for “order”) ?

Big O notation messure how long it will take an algorithm to run based on how the inputs the increase. 

Big O notation benchmarks based on the numbers on inputs 

The reason why as software developers we use Big O notation is because we want to know how well an algorithm will perform as it scales. 


why are Big O question asked during technical interviews?

Well my guess is companies want to find out if you can not only code but also know how to optimize and find the best solution for a problem.

n represents the number of inputs 


With Big O always assume the input is infinite 
and base your benchmark off of that.


The size of the input and the order that the input is in can have an effect on
the performance of the algorithm.



O(1) - runs in linear time meaning it will have the same runtine or(space) regardless of the size of the inputs.



O(N) - runs linearly and in proportion to the size of the input data meaning the run time will increase based on the number of inputs. so if the input increases by 2 it will take twice as long to run 

O(N^2) - runs directly proportional to the square of the size of the input data 

This algorithm will take 4 times as long for twice as much data 

This runtime is common with nested for loops 
when you add more nested for loops for example three nested for loops the runtime will increase from O(N^2) O(N^3)

O(2^n) - takes double the time for every input given to the function

O(log N) - doubling the input of the data will have little affect on the run time 
O(n log n)

