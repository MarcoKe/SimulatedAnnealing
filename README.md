This repository contains a simple implementation for the optimization algorithm Simulated Annealing. It has been written to be generic, so it can be easily adapted to arbitrary optimization problems. 

The code contains a simple example for TSP problems. To apply it to further optimization problems, you can simply create a new class that interits from SimulatedAnnealingOptimizer and overwrites the step() and energy() methods with ones that are suitable to your problem. 

The code is written for minimization problems. You will have to make some changes for maximization problems. Alternatively, you can simply reformuluate your objective function. 
