# 1D Beam Element Analysis Using ANSYS Mechanical

## Overview

This project presents the structural analysis of a beam using 1D beam elements in ANSYS Mechanical.

The objective was to determine the stress and deformation of the beam under the specified loading and boundary conditions and validate the numerical results against the analytical solution.

The beam was first evaluated using hand calculations, followed by finite element analysis using 1D beam elements.

---

## Objectives

- Perform structural analysis of a beam using 1D beam elements.
- Apply the required material properties, loading and boundary conditions.
- Generate an appropriate finite element model.
- Determine the maximum stress and total deformation.
- Compare the ANSYS results with the analytical solution.
- Understand the application of 1D beam elements in structural analysis.

---

## 1D Beam Model

The beam was represented using 1D beam elements in ANSYS Mechanical.

### Beam Geometry and Cross-Section

![1D Beam Cross Section](1D%20Beam%20with%20Cross%20section.png)

### Complete Model Setup

![Beam with Applications](Beam%20with%20all%20Applications.png)

The model includes the required loading and boundary conditions for the structural analysis.

---

## Meshing

The beam was discretized using 1D beam elements.

### 1D Beam Mesh

![1D Beam Mesh](1D%20Beam%20mesh.png)

The mesh was generated along the beam length to represent its structural behavior using beam elements.

---

## Results

### Total Deformation

The total deformation of the beam obtained from the ANSYS analysis is shown below.

![1D Total Deformation](1D%20Total%20Deformation.gif)

### Maximum Combined Stress

The maximum combined stress obtained from the analysis is shown below.

![1D Maximum Combined Stress](1D%20Max%20Combined%20Stress.gif)

---

## Analytical Validation

The ANSYS 1D beam-element results were compared with the results obtained from analytical beam calculations.

| Parameter | Analytical | 1D ANSYS |
|-----------|------------|----------|
| Maximum Stress | 375 MPa | 375 MPa |
| Maximum Deformation | 0.785 mm | 0.785 mm |


---

## Engineering Observation

The 1D beam-element model provides an efficient method for analyzing beam structures while requiring significantly less geometric representation than a full 3D solid model.

The obtained stress and deformation results can be validated against classical analytical beam theory to assess the accuracy of the finite element model.

---

## Conclusion

The beam was successfully analyzed using 1D beam elements in ANSYS Mechanical.

The resulting stress and deformation were compared with analytical calculations to validate the finite element model.

This analysis demonstrates the use of 1D beam elements for efficient structural analysis and the importance of validating FEA results against theoretical calculations.

---

## Software Used

- ANSYS Mechanical
- Engineering Beam Theory
- Microsoft Excel / Calculator

---

## Skills Demonstrated

- Finite Element Analysis (FEA)
- Structural Analysis
- 1D Beam Element Modelling
- Meshing
- Boundary Conditions
- Stress Analysis
- Deformation Analysis
- FEA Post-processing
- Analytical Validation
