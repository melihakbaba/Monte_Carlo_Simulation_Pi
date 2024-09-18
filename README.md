## Monte Carlo Simulation for Pi (π)

I tried to estimate the value of Pi using a Monte Carlo Simulation. The iteration limit was set to 1000. For easier visualization, the random numbers were fixed by setting the seed to 99.



The following graph belongs to a Monte Carlo Simulation.

<img src=https://github.com/melihakbaba/Monte_Carlo_Simulation_Pi/blob/8288e92f205bf32cecfa3351fd4a6e5cd47b15fa/Monte_Carlo_Sim.png width="650"/>

Later, I ran the Monte Carlo simulation 10,000 times and saved the estimated (converged) value of pi at the end. According to the central limit theorem, the distribution of the sample means from a distribution will follow a normal distribution. Since the logic of the Monte Carlo simulation involves weighted averages, these pi values I saved will also follow a normal distribution.I made a more reliable estimate by taking the average of the pi predictions I saved. 

The graph below shows the distribution of the pi estimates and their average.

<img src=https://github.com/melihakbaba/Monte_Carlo_Simulation_Pi/blob/8288e92f205bf32cecfa3351fd4a6e5cd47b15fa/Density%20Plot%20of%20Pi%20Estimates.png width="650"/>


