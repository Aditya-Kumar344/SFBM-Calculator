# Beam Analysis & SFBM Calculator


Engineers often face the tedious and time-consuming task of manually building shear force and bending moment diagrams for simple beams subject to complex loads. A single calculation error can force a complete restart of the process.

This project is an **efficient SFBM Diagram Calculator** designed to automate this workflow. By leveraging **SymPy** for analytical computation and **Matplotlib** for visualization, this tool calculates support reactions, shear forces, bending moments, slopes and deflections for statically determinate beams.

It serves as both a practical tool for quick analysis and an educational resource for students wishing to verify their manual calculations or generate infinite practice problems.

## 🛠️ Tech Stack
* **Python 3**: Core logic.
* **SymPy**: Used for symbolic mathematics to solve equilibrium equations and integration for slope/deflection.
* **Matplotlib**: Used for rendering the 2D diagrams and plots.
  
## ✨ Key Features

This calculator supports statically determinate beams subject to a variety of load conditions:

-  **Point Loads:** Concentrated forces applied at specific coordinates.
-  **Point Moments:** Concentrated moments applied at specific coordinates.
-  **Uniformly Distributed Loads (UDL):** Constant load spread across a span.
-  **Linearly Varying Loads (UVL):** Triangular or trapezoidal loads.

## 📖 Outputs
- Automatic calculation of Support Reactions.
- Analytical equations for Shear Force and Bending Moment.
- Calculation of Slope and Deflection profiles.
- **Dynamic Plotting:** clear, interpretable visualization of SF and BM diagrams.
