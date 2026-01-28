# Stochastic Differential Equations (SDEs)
Coursework and independent study project from **UC San Diego Math 214** and an **independent study in stochastic calculus**, focused on **simulating, analyzing, and validating SDE models**.

## What is an SDE?
An SDE models a state variable with both deterministic drift and random fluctuations, typically written 

$dX_t = b(X_t,t)dt + \sigma(X_t,t)dB_t$

where $B_t$ is Brownian motion.

## Example output
Below is a Monte Carlo visualization of simulated SDE paths over time (sample trajectories, density shading, and summary statistics).

![Simulated SDE paths and empirical density](Nurmerical%20solutions/sde_paths_density_plot.png)

## What this project covers
- **Ito calculus foundations** (Ito integral, Ito formula, existence/uniqueness concepts)
- **Numerical SDE solvers** (From basic methods such as Euler–Maruyama and to more advanced methods depending on the model)


This is intentionally kept simple and self-contained: the goal is to demonstrate correct stochastic modeling workflow end to end, from SDE specification to simulation, diagnostics, and interpretation.

