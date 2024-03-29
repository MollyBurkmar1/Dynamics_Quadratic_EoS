# Dynamics of Dark Matter, Radiation and Dark Energy with a Non-Linear Quadratic Equation of State

## Prerequisites

To run this notebook, the user requires a Mathematica license and to have installed MaTeX (see https://github.com/szhorvat/MaTeX).

To avoid a Git large file error, a Git hook has been added which clears the output when the file is committed. To set the hooks directory to the .githooks folder, the following command needs to be run in your local directory where you've pulled this repository: 

git config --local core.hooksPath .githooks/

## Analysis

The analysis in this notebook is used in the following paper: https://arxiv.org/abs/2302.03710v2.

In this notebook, a system of differential equations describing standard dark matter and radiation, the Hubble expansion, and dark energy with a non-linear quadratic equation of state (EoS) is analysed. Non-singular bouncing models are the generic closed model when only dark matter with the quadratic EoS considered here is present. The aim of this analysis is to understand the effect dark matter and radiation have on these closed bouncing models. The full system is 4-dimensional, therefore we project the dynamics on to 2-dimensional and 3-dimensional planes by integrating the differential equations for dark matter and radiation with respect to the dark energy.

The analysis in the notebook provides:

+ the fixed points of the full system of equations and the sub-manifolds with their eigenvalues,
+ analysis of the range of Einstein fixed points that can be admitted by the system
+ calculations of the values of the first integrals needed for each dynamical case,
+ plots of the sub-manifolds with their potentials,
+ plots of each dynamical case in the full system in terms of different variables in 2-dimensions (with their potentials) and in 3-dimensions.

We also investigate a similar system, except we enforce an upper bound on the matter and radiation components. This analysis includes:

+ the fixed points of the system with their eigenvalues,
+ analysis of the range of Einstein fixed points possible,
+ calculations of the values of the first integrals needed to produce the different dynamical cases, 
+ plots of the phase spaces with their potentials in 2-dimensions.
