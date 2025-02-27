# FDTD-Simulations
Finite-Difference Time-Domain Simulations of Electromagnetic Waves in 2D between different media

This repository contains a Pluto.jl notebook implementing a Finite-Difference Time-Domain (FDTD) simulation of electromagnetic waves in 2D. The notebook explores wave propagation, scattering, and interactions with different materials, including PEC (Perfect Electric Conductor) boundaries and dielectric interfaces. <br>

**Topics included in  the notebook: <br>**
Maxwell's Equations Implementation: Simulates electromagnetic wave behavior using discretized TE-mode (Transverse Electric) equations. <br>
Yee Cell & Staggered Grid: Ensures numerical stability and accuracy. <br>
Custom Excitations: Supports point sources and plane waves. <br> 
Material Interfaces & PEC Boundaries: Includes simulations with scattering from PEC objects and wave refraction at dielectric boundaries. <br>
Interactive Visualization: Uses PlotlyJS.jl for animated 3D field visualization. <br>

**Requirements <br>**
Before running the notebook, ensure you have Julia 1.8+ and install the required dependencies: <br>
import Pkg <br>
Pkg.add(["Pluto", "PlutoUI", "PlutoTeachingTools", "Plots", "PlotlyJS", "LinearAlgebra"]) <br>

**How to Run <br>**
1. Open Julia and start Pluto.jl: <br>
import Pluto (or use: using Pluto) <br> 
Pluto.run() <br>

2. Load the Assignement_FDTD-Giovanna-Rizkallah.jl notebook. <br>
Run all cells to execute the simulation and visualize results. <br>

**Visualizations <br>**
The notebook includes animations to visualize wave propagation, scattering, and interactions with interfaces. <br>
