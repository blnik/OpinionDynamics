# OpinionDynamics
The repository contains all the code that was used to create the plots for the report

Some of the code takes a while to run and is therefore commented out. The corresponding results of the code that is commented out can be found in the `savedResults` directory.

## Hegselmann-Krause models
Code available in `HK.ipynb`
- **Figure 1.1:** some basic sample simulations
- **Figure 1.4:** comparison: average number of clusters, 2R-conjecture, trace method (symmetric case)
- **Figure 1.5:** average number of clusters on (e_l, e_r)-grid
- **Figure 1.6:** comparison: average number of clusters, 2R-conjecture, trace method (fixed asymmetry)
- **Figure 1.7:** same as 1.6 for larger e_l, e_r
- **Figure 1.8:** sample simulations fixed asymmetry
- **Figure 1.11:** comparison: average number of clusters, 2R-conjecture, trace method (opinion dependent asymmetry)

## ODE models
Code available in `ODE.ipynb`
- **Figure 2.1:** sample simulations (comparison sum and average of differences)
- **Figure 2.2:** comparison average number of clusters (sum and average of differences)
- **Figure 2.3:** average number of clusters on (e_l, e_r)-grid
- **Figure 2.4:** sample simulation opinion dependent asymmetry
- **Figure 2.5:** average number of clusters for opinion dependent asymmetry: (e,m)-grid

## SDE models
Code available in `SDE.ipynb`
- **Figure 3.1:** sample simulation naive SDE model
- **Figure 3.3:** simulation of expected trajectories
- **Figure 3.4:** sample simulations with order parameter
- **Figure 3.5:** average order parameter on (e, s)-grid
- **Figure 3.6:** sample simulations for specific points on grid
- **Figure 3.8:** sample simulations fixed asymmetry
- **Figure 3.9:** sample simulations fixed asymmetry with mean
- **Figure 3.10:** average period of mean

## PDE models
- **Figure 4.1:** sample simulations symmetric PDE model
- **Figure 4.2:** peak position and time derivative at time 0 and `x=0.5` on (e, s)-grid
- **Figure 4.5:** sample simulations asymmetric PDE model
- **Figure 4.6:** position of peak as function of time
- **Figure 4.7:** period of peak as function of s
