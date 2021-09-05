# CMTH-2
MSci Project Code: [CMTH-2] (2020-2021) 
# Simulating Materialsa at Constant Pressure Using Homogeneous Coordinates
Run code from equilibrium state for best results:
1) Run code at desired target pressure (aout a few GPa) using Routine 1; use the lattice structure to begin with and the Boltzmann distribution for initial velocities of the particles, with W=10e6 (cell parameter) until thermalisation (each dof has 3/2 kBT of energy). 
2) Then run the simulation again using Routine 2; set "lam_fin" equal to the final value of lambda from first run, load the final positons into "Is" and final atomic velooties into "Ivs". 
This is all for any value of W (note that W affects dynamics).
