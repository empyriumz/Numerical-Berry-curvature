# Numerical-Berry-curvature
Numerical implementation of Berry curvature calculation for tight binding Hamiltonians.

This numerical routine has been used for calculating the magneto-tranpsort properties in several topological materials.

See [Phys. Rev. Lett. 119, 166601](https://journals.aps.org/prl/abstract/10.1103/PhysRevLett.119.166601) for results.

## Usage
This Mathematica notebook is a demo for a 4*4 Hamiltonian describing the low-energy effective model of Bi2Se3 in the presence of z-direction external magnetic field.

Assuming the fermi level cross the upper bands, the demo calculates the Berry curvature as well as orbital moment distribution in the discretized k-space. 

You can subsitute your own non-interacting Hamiltonian and model parameters to do the calculations.
Please cite [PRL. 119, 166601](https://journals.aps.org/prl/abstract/10.1103/PhysRevLett.119.166601) if you have used this script in your scientific publications.

## Requirement
Tested in Mathematica 10.0 and higher versions.

Optional: [MaTeX](https://github.com/szhorvat/MaTeX) package for using LaTeX in Mathematica


