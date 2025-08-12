# RANS-Approach-to-2D-Shear-Mixing-Flow
Numerical study of the 2D Delville shear layer using the RANS approach with the Spalart–Allmaras turbulence model in ANSYS Fluent. Includes mesh sensitivity analysis and validation against NASA experimental data to evaluate model performance in shear-dominated turbulent flows.

This repository presents a numerical study of a 2D shear mixing layer (Delville shear layer) using the Reynolds-Averaged Navier-Stokes (RANS) equations with the Spalart–Allmaras (SA) turbulence model in ANSYS Fluent. The simulation is part of a turbulence model validation effort against NASA’s experimental benchmark data.

## Project Summary

- **Objective**: Validate the performance of the SA turbulence model for a 2D turbulent mixing layer.
- **Case**: Delville shear layer (NASA Turbulence Modeling Resource).
- **Solver**: ANSYS Fluent (Student Version).
- **Comparisons**: Velocity profiles and turbulent viscosity compared with experimental data.
- **Mesh Sensitivity Study**: Meshes from 29K to 116K cells were tested.
- **Outcome**: SA model captures near-field shear behavior reasonably well but shows limitations in far-field predictions, particularly in resolving large-scale vortical structures.

## Tools and Methods

- **ANSYS Fluent (Student Version)** for CFD modeling.
- **Spalart–Allmaras (SA)** model under the RANS framework.
- Structured and unstructured mesh variations (29K–116K cells).
- Post-processing and plotting tools (e.g., ANSYS CFD Post, Excel).

## 📁 Repository Structure
├── meshes/ # Mesh files (.msh or export)
├── case-files/ # Fluent case and data files
├── plots/ # Velocity profiles, contour plots, etc.
├── report/ # Final report or summary PDF (optional)
├── LICENSE # CC BY-NC 4.0 License
└── README.md # This file

## License

This work is licensed under the [Creative Commons Attribution-NonCommercial 4.0 International License (CC BY-NC 4.0)](https://creativecommons.org/licenses/by-nc/4.0/).

> You are free to share and adapt this work for non-commercial purposes with proper attribution. Commercial use is not permitted.

## Acknowledgment

The author gratefully acknowledges ANSYS Inc. for providing access to the ANSYS Student Version of their simulation software. This powerful tool has been instrumental in enabling the computational modeling and analysis presented in this work.

For more information on the ANSYS Student Version, visit the [ANSYS Academic Student Portal](https://www.ansys.com/en-in/academic/students).

## Usage Disclaimer

The ANSYS Student Version software used in this project is licensed solely for **educational and personal development purposes**.  
All simulations and results generated using this software comply with the terms and conditions set forth by ANSYS Inc.  
**This repository is intended for academic sharing only and is not for commercial use or financial gain.**

---

### Contact

For questions or collaboration, feel free to reach out to Vinay Kumar V via GitHub or email.

