# The-wave-disturbance-data-and-multihull-data
# Data and Results for Anti-Pitching Control Study

This repository contains the MATLAB `.mat` data files used in the paper **“Efficient Predictive Anti-Pitching Control of High-Speed Multihull Ships Based on Sparse Spectrum Gaussian Process Regression”**. The data files support the simulation results for various anti-pitching control strategies on a multihull ship model.

## Files:
1. **Wave.mat** - Contains wave disturbance force and moment data used in the simulation.
2. **SSGP_PTC_MPC.mat** - Contains simulation results for the multihull using the SSGPR-based PTC MPC control strategy.
3. **No_Controller.mat** - Contains simulation results for the multihull without any control.

## How to Load the Data:
In MATLAB, load the data using the `load` command. Example:
```matlab
load('wave.mat');
load('SSGP_PTC_MPC.mat');
load('No_Controller.mat');
