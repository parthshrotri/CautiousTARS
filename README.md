# Cautious TARS #
-When TARS has a 100% safety setting

Hello! I assume if you're looking at this page, you're either lurking through my projects (I'm flattered) or you're here to grade my AA548 Final Project entitled: Convex Methods for Spacecraft Rendezvous and Docking.

If you're here lurking, perhaps take a look at my report which is available for download in this repo

This work demonstrates how spacecraft rendezvous and docking, a problem with non-linear dynamics and non-convex safety constraints can be solved using the Clohessy-Wiltshire relative dynamics formulation as well as sequential convex programming.

If you would like to run this simulation, you will need to download jax, numpy, cvxpy, plotly, and tqdm.

Simply hit run all cells in "simulation.ipynb" to run the simulation and see the plots and visualization. 

Note that the 3d model for the Dragon capsule was downloaded from [thingiverse](https://www.thingiverse.com/thing:4207259) and is not my own.

If you want to see the 3D animations of the rendezvous and docking, you'll need to download the USDZ file for yourself from [NASA's website](https://science.nasa.gov/resource/international-space-station-3d-model/) and then convert it to an STL.
