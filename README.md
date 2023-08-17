# Computational-Fluid-Dynamics

Numerical Simulation and Stream Function Computation
This repository contains Python code for two distinct tasks: numerical simulation of the advection equation 
using various finite difference schemes, and computation of the stream function using the Point Jacobi iterative method.

Advection Equation Numerical Simulation
The advection_simulation.py script performs numerical simulations of the advection equation using different finite difference schemes. 
The advection equation describes the transport of a quantity through a medium at a constant speed. The script allows users to explore 
different initial conditions and observe the evolution of the solution using various schemes.

Stream Function Computation
The stream_function_computation.py script implements the Point Jacobi iterative method to compute the stream function in a 
two-dimensional domain. The stream function is used to visualize fluid flow patterns.

Prerequisites
Python 3.x
NumPy
pandas
Matplotlib

Usage
Clone this repository: git clone https://github.com/22m0052-Rajat/Computational-Fluid-Dynamics.git
Navigate to the repository: cd Computational-Fluid-Dynamics
Run the simulation script: Computational-Fluid-Dynamics.ipynb
Follow the on-screen prompts to provide input for CFL values and choose initial conditions and 
difference schemes. The script will generate plots showing the evolution of the solution for different CFL values and schemes.
