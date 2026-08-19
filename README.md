# Numerical Investigation of Flow Losses in a 2D Tesla Valve

CFD investigation of turbulent reverse flow through a 2D Tesla valve using **ANSYS Fluent**.

The project studies the main flow-loss mechanisms occurring in a Tesla valve, with particular focus on pressure drop, velocity fields, turbulence generation, and the interaction between the side-branch jet and the main channel.

## Methodology

A simplified two-dimensional Tesla valve geometry was analysed using steady-state RANS simulations.

Two turbulence models were compared:

- Realizable k-ε
- SST k-ω

Different mesh resolutions and near-wall treatments were investigated, with approximately:

- y+ ≈ 30 for the Realizable k-ε model
- y+ ≈ 1 for the SST k-ω model

The numerical results were compared with published benchmark data for turbulent Tesla-valve flow.

## Main Results

The simulations reproduced the main flow mechanisms observed in the benchmark:

- strong acceleration in the merging region;
- transverse flow deflection caused by the side-branch jet;
- increased turbulent kinetic energy near the recombination region;
- nonlinear increase of pressure drop with Reynolds number.

The **SST k-ω model** provided the closest agreement with the benchmark pressure-drop results, with a deviation of approximately **3% at Re = 50,000**.

The Realizable k-ε model predicted lower pressure losses and a smoother flow field.

## Tools

- ANSYS Fluent
- Computational Fluid Dynamics (CFD)
- RANS turbulence modelling
- Mesh sensitivity analysis
- Benchmark validation

## Report

The complete project report is available here:

[View the CFD Report](Tesla_Valve_CFD_Report.pdf)

## Authors

Francesco Trevisi, Dante Serrecchia, Pietro Corsani Pio  
Delft University of Technology — Faculty of Mechanical Engineering
