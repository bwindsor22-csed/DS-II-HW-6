# DS-II-HW-6

Write a program that times the amount of time it takes to add a random list of int’s in the range 1-100. The size of the list shall be 100_000_000.
Add the numbers using 1,2,4,8,16,32,64,128,256,512,1024 threads and store the number of milliseconds required
Implement method long listSum(int []list, int threads)
which returns the sum of the items in the list using the specified number of threads by evenly (or nearly so) load balancing the work among the specified threads.

Your main program must output the best choice for number of threads for your system. (It will likely be different dependent on number of cores and other factors). Include that value in a  comment

