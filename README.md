# Multiobjective Knapsack Problems

[link to subject](http://home.ku.edu.tr/~moolibrary/)

The multiobjective knapsack problem consists of n objects, rth object in the knapsack has a positive integer weight wr and p non-negative integer profits vjr where p represents number of objective functions. The knapsack has a positive integer capacity W. Decision variable xr denotes whether item r is selected for the knapsack or not.

The multiobjective knapsack problem instances are generated for p=3, 4 and 5 cases, and vjr and wr are random integers drawn from the interval [1,1000] where j∈{1,…,p} and r∈{1,…,n}. The capacity of the knapsack is calculated as W=⌈0.5(∑nj=1wj)⌉. The total number of data files for the multiobjective knapsack problem is 160. 100, 40 and 20 of the instances have p=3, p=4 and p=5 numbers of objective functions, respectively. The data file names are given in the following format, "KP_p-X_n-Y_ins-Z.dat." KP stands for the knapsack problem, X represents the number of objective functions, Y shows the number of objects, and Z is the instance number. The format of each data file is:  
- Number of objective functions (p).
- Number of objects (n).
- Capacity of the knapsack (W∈ℤ).
- Profits of the objects in each objective function, ℤp×n.
- Weights of the objects (w∈ℤn).

To resolve this problem, i made a simple notebook named 'resolveProblem.ipynb'