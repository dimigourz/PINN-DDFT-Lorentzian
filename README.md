# Physics-Informed Neural Networks for Nonlocal Gradient Flows in DDFT

This repository accompanies the manuscript:

**A Physics-Informed Neural Network with a Modified Lorentzian Activation for Nonlocal Gradient-Flow Equations in Dynamic Density Functional Theory**

**Authors:** Dimitrios Gourzoulidis, Soumaya Elkantassi, and Serafim Kalliadasis.

## Overview

We study physics-informed neural networks (PINNs) for nonlinear and nonlocal gradient-flow equations arising in dynamic density functional theory (DDFT). The approach uses a modified Lorentzian activation function,

$$
\sigma_\varepsilon(z) = \frac{z\varepsilon^2}{z^2+\varepsilon^2},
$$

to improve training convergence relative to the standard `tanh` activation.

The numerical study examines accuracy against analytical or finite-element reference solutions and evaluates mass conservation and free-energy dissipation.

## Numerical experiments

The manuscript considers four examples:

1. **Nonlocal interaction in one dimension** — comparison with a known stationary solution.
2. **Nonlinear diffusion in a double-well potential** — evolution toward a bimodal density profile.
3. **Nonlinear diffusion with nonlocal attraction** — dynamics governed by an attractive interaction kernel.
4. **Two-dimensional droplet coalescence** — merging droplets in a DDFT model with attractive interactions and excluded-volume effects.

## Code availability

The experiment implementations and reference data have not yet been added to this repository. They will be included after verification against the manuscript's reported results.

## Citation

If you use this work, please cite:

D. Gourzoulidis, S. Elkantassi, and S. Kalliadasis, *A Physics-Informed Neural Network with a Modified Lorentzian Activation for Nonlocal Gradient-Flow Equations in Dynamic Density Functional Theory* (manuscript, 2026).
