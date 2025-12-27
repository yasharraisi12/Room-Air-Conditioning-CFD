# 3D Indoor Airflow & Thermal Comfort Analysis using OpenFOAM

## 📌 Project Overview
This project presents a high-fidelity CFD simulation of indoor airflow and heat distribution within a furnished room.
---
---

## 📊 Visual Analysis & Results

### 1. Global Airflow Pathlines (Top View)
![Top View](TopView_Airflow_Pathlines.png)

### 2. 3D Velocity Vortex Structure
![Velocity Vortex](3D_Velocity_Vortex.png)

### 3. Advanced Flow Vortex Analysis
![Flow Analysis](3D_Flow_Vortex_Analysis.png)

### 4. Thermal & Vector Field Analysis
![Thermal Vector](Thermal_Vector_Field_Analysis.png)

### 5. Velocity Magnitude Distribution
![Velocity Magnitude](Velocity_Magnitude_Distribution.png)

---
## 🛠 Technical Workflow & Numerical Specs

| Parameter | Specification |
| :--- | :--- |
| **Solver** | `buoyantSimpleFoam` |
| **Turbulence Model** | RAS `k-Epsilon` |
| **Total Cells** | **741,946** |
| **Max Non-Orthogonality** | 37.42 |
| **Max Aspect Ratio** | 2.44 |
| **Total Volume** | 149.17 m³ |

### 🧩 Mesh Breakdown (checkMesh Results)
- **Hexahedra:** 674,032 cells
- **Polyhedra:** 67,914 cells
- **Mesh Status:** All topology and geometry checks **OK**.

## 🚀 Key Findings
- **Zero Errors:** The mesh passed all topology and geometry checks.
- **Ventilation Efficiency:** Optimized air inlet paths successfully minimize stagnant zones.
- **Thermal Stability:** Accurately captures stable thermal gradients.

---
**Developed by:** 
                Yashar raisi

