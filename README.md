# PSO-transport
Implementation of PSO for transportation problem 

# Issue
A company wants to visit a certain number of stores optimally given a k number of available transports.

## The following restrictions are contemplated:

1. Total duration in stores are similar in each transport.
2. Areas covered by each transport must be similar.


## Objective.
1. minimize the standard deviation of time (duration by transport in a store) in the found clusters.
2. minimize the standard deviation of the total area in the found clusters.

## Solution:

Due to the nature of the problem, PSO-MOhv algorithm was implemented, a multiobjective PSO based on hyper-volume.
