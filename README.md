# Optimal Integration of EV Charging Stations and Capacitors

## Overview

This repository contains scripts and data to reproduce the results of the paper titled "Optimal Integration of EV Charging Stations and Capacitors for Net Present Value Maximization in Distribution Network." The proposed hybrid approach utilizes Genetic Algorithm (GA) and Particle Swarm Optimization (PSO) for optimizing the placement of Electric Vehicle Charging Stations (EVCS) and Capacitors (CAP) in a distribution network.

## Key Features

- **Hybrid Method**: Combines GA and PSO for efficient optimization.
- **Reduced Power Loss**: Significant reductions in active power loss across various test systems.
- **Cost Savings**: Maximizes financial savings by optimizing installation and maintenance costs.
- **V2G Capability**: Enables electric vehicles to return power to the grid, enhancing stability.

## Files Description

- **/scripts/**: Contains Python scripts for running simulations and analyses.
  - `optimize_evcs_cap.py`: Main script for optimizing EVCS and CAP placement.
  - `load_flow_analysis.py`: Script for performing load flow analysis on the distribution network.
  - `results_analysis.py`: Script for analyzing and compiling results from simulations.

- **/data/**: Contains input data files for different bus systems.
  - `ieee_33_bus.csv`: Data for the IEEE 33-bus system.
  - `ieee_69_bus.csv`: Data for the IEEE 69-bus system.
  - `ieee_85_bus.csv`: Data for the IEEE 85-bus system.
  - `ieee_118_bus.csv`: Data for the IEEE 118-bus system.
  - `brazil_136_bus.csv`: Data for the Brazil 136-bus system.

- **/results/**: Contains output files and visualizations.
  - `table_results.csv`: Summary of results, including power loss and cost savings.
  - `voltage_profiles.png`: Graphical representation of voltage profiles across different scenarios.

## How to Run

1. Clone this repository to your local machine:



The proposed Hybrid GA-PSO Optimization Approach is simulated with a system output voltage of 11 kV and 100 MVA power rating.
Advantages:
1.	Fewer components needed: The hybrid method optimizes placement of capacitors (CAP) and electric vehicle charging stations (EVCS) efficiently.
2.	Improved system performance: Reduces power loss and improves voltage levels across the grid.
3.	Cost-effective: Maximizes financial savings by reducing energy loss and considering installation and maintenance costs.
4.	Vehicle-to-Grid (V2G) enabled: EVs can send power back to the grid during high demand, improving grid stability.
Working:
Four cases were studied:
1.	Base case (no EVCS or CAP).
2.	EVCS added.
3.	Both EVCS and CAP added.
4.	EVCS with V2G mode.
Simulations were conducted, and results showed reduced power loss and improved voltage.
Key Specifications:
•	Systems tested: IEEE 33, 69, 85, 118, and Brazil 136-bus.
•	Power rating: 100 MVA.
•	Operating voltage: 11 kV.
Results:
Significant reductions in power loss and cost savings were observed across all systems, with the hybrid method performing better than other algorithms.
Disadvantage:
Convergence time is slightly longer for larger systems.
Applications:
This method is useful for Electric Vehicle Charging, Smart Grids, Renewable Energy, and Military Power Systems, ensuring better grid reliability and efficiency.

