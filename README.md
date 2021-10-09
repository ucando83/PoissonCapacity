# PoissonCapacity
Capacity-achieving input distributions for the Poisson channel with peak amplitude constraint

This folder contains one .mat file for each value of the dark current parameter \lambda = {0, 1, 10, 100}.

Each .mat file contains 3 variables: 
- dc: value of the dark current parameter
- opt_pos_input: matrix that reports the positions of the support points of the capacity-achieving distribution. Each row corresponds to a value of the peak amplitude constraint A. Since 0 and A are always part of the solution, 0 will always be the value stored in the first column, and A the value stored in the last column.
- opt_prob_input: matrix that reports the probabilities of the support points of the capacity-achieving distribution. Each row corresponds to a value of the peak amplitude constraint A.
