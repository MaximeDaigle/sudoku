# Sudoku

## Algorithms
There is 4 algorithms to solve sudoku.
The first one is use to benchmark the others and was written by Peter Norvig, director of research at Google Inc. (source: http://www.norvig.com/sudoku.html). It uses constraint propagation.

The second algorithm is Hill-Climbing. It's an algorithm that finds the local optima.

The third one is Simulated annealing. It's in the Markov Chain Monte Carlo (MCMC) family.

The last one is the program of Norvig with an additional constraint from http://www.angusj.com/sudoku/hints.php

## Results on 1000 sudoku
Norvig 
  Solved: 1000/1000 
  Times (min: 0.00, avg: 0.00, max: 0.01, std dev.: 0.0009) 
  Visited nodes (min: 271, avg: 326.00, max: 1073, std dev.: 73.2307)

Hill climbing 
  Solved: 421/1000 
  Times (min: 0.02, avg: 0.03, max: 0.13, std dev.: 0.0184) 
  Visited nodes (min: 96, avg: 210.00, max: 332, std dev.: 76.6414)

Simulated annealing 
  Solved: 983/1000 
  Times (min: 0.00, avg: 0.17, max: 1.14, std dev.: 0.2056) 
  Visited nodes (min: 162, avg: 271.00, max: 395, std dev.: 36.7383)

Additional Constraint 
  Solved: 1000/1000 
  Times (min: 0.00, avg: 0.01, max: 0.09, std dev.: 0.0092) 
  Visited nodes (min: 271, avg: 317.00, max: 1013, std dev.: 54.5300)

## Results on the hardest sudoku
Norvig 
 Solved: 1/1 
 Times (min: 70.07, avg: 70.07, max: 70.07, std dev.: nan) 
 Visited nodes (min: 6542708, avg: 6542708.00, max: 6542708, std dev.: nan)
 
Hill Climbing 
 Solved: 0/1 
 Times (min: 0.10, avg: 0.10, max: 0.10, std dev.: nan) 
 Visited nodes (min: 74, avg: 74.00, max: 74, std dev.: nan)

Simulated annealing
 Solved: 1/1 
 Times (min: 0.20, avg: 0.20, max: 0.20, std dev.: nan) 
 Visited nodes (min: 192, avg: 192.00, max: 192, std dev.: nan)
 
Additional Constraint 
 Solved: 1/1 
 Times (min: 209.17, avg: 209.17, max: 209.17, std dev.: nan) 
 Visited nodes (min: 1873971, avg: 1873971.00, max: 1873971, std dev.: nan)
