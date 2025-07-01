# Leverage-project

This project aims to optimize the selection of exoplanet targets for **Tier 2 observations** with ESA’s upcoming **Ariel mission**, focusing on maximizing observational **diversity and scientific return** under realistic time constraints.

The foundation of this work builds on the target list presented in Edwards et al. 2020 which proposed a curated set of Tier 2 targets using fixed criteria, later referred as MCS (Mission Candidate Sample). While the baseline list is carefully selected, we seek to go further by quantifying and optimizing the leverage each planet contributes to Ariel’s overall science goals. The leverage have been explored in the following paper: 

Building up on this last paper, we are exploring here optimization methods, including:

- **Simulated Annealing**  
  A stochastic search algorithm that avoids local optima by gradually reducing randomness (temperature) over time.

- **Quantum Annealing** 
  Using quantum-inspired methods to explore the high-dimensional solution space more efficiently.

We compare the results of these optimization strategies against Nic’s original selection, analyzing how many MCS targets are selected and whether the leverage and diversity are improved under time constraints (a 3-year Tier 2 observation window).

This work supports the broader goal of ensuring Ariel delivers the most diverse and scientifically valuable sample of exoplanet atmospheres within mission limits.
