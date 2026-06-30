Galactic Spiral Arm Maintenance Models
This repository contains the Python scripts developed for the research paper: "Asymmetric Kinetic Feedback from Core-Collapse Supernovae as a Structural Delay Margin in Spiral Arms" (Tolba, 2026).
Overview
These codes implement the analytical models to quantify the "Champagne Flow" counter-torque exerted by core-collapse supernovae (SNe) on galactic spiral arms. The study rigorously demonstrates that this mechanism contributes a ~5.8% structural delay margin, opposing the kinematic winding of spiral arms.  
Repository Contents
code_01_torque_budget: Calculates the dissipative counter-torque (tau_ejecta) vs. kinematic shear torque (tau_wind).
code_02_winding_evolution: Numerical integration code generating Figure 1 (Winding Angle vs. Time).
code_03_monte_carlo: 3D geometric Monte Carlo model to validate the momentum asymmetry fraction (f_asym = 5.6% ± 8.9%).
code_04_sensitivity_sweep: Sensitivity analysis of f_asym relative to the Sedov-Taylor cooling radius (R_cool), generating Figure 2.
Dependencies
pip install -r requirements.txt (requires numpy, matplotlib).
Citation
Please cite this work as:
Tolba, O. (2026). Asymmetric Kinetic Feedback from Core-Collapse Supernovae as a Structural Delay Margin in Spiral Arms. [Provide DOI from Zenodo].
