3D Indoor Airflow & Thermal Comfort Analysis using OpenFOAM
📌 Project Overview
This project presents a high-fidelity Computational Fluid Dynamics (CFD) simulation of indoor airflow and heat distribution within a furnished room. The study focuses on evaluating ventilation efficiency and identifying stagnant zones (Dead Zones) using steady-state buoyant solvers.

🛠 Technical Workflow & Numerical Specs
📈 Convergence Performance
The simulation reached high precision with excellent stability. The final residuals:

Velocity (U): 4.1e-03

Pressure (p_rgh): 4.6e-03

Enthalpy (h): 2.9e-03

📊 Visual Analysis & Results
1. Global Airflow Strategy (Top View)
Strategic map showing the full coverage of ventilation. Blue zones indicate low-velocity regions effectively managed by the vortex.

2. 3D Velocity Vortex Structure
3D visualization of air circulation. The spiral formation demonstrates the impact of furniture on flow momentum.

3. Advanced Flow Vortex Analysis
Detailed 3D analysis of vortex formation within the room volume, showing the interaction of air streams.

4. Thermal & Vector Field Analysis
Mapping of heat transport and vector fields, showing how buoyancy-driven flow interacts with forced convection.

5. Velocity Magnitude Distribution
Surface and volumetric distribution of velocity magnitude, highlighting the effective air reach.

🚀 Key Findings
Stagnant Zone Reduction: Optimized inlet velocity minimizes air stagnation in corners.

Thermal Stratification: Captures buoyancy effects and stable thermal gradients.

Mesh Independence: High resolution (~0.75M cells) ensures boundary layer accuracy.