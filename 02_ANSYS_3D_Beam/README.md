# 3D Beam Analysis Using ANSYS Mechanical

## Overview

This project presents the finite element analysis (FEA) of a beam using
3D solid elements in ANSYS Mechanical.

The objective was to determine the stress and deformation of the beam
under the specified loading and boundary conditions and compare the
numerical results with the analytical solution and the corresponding
1D beam-element analysis.

---

## Objective

The main objectives of this analysis were:

- Model the beam as a 3D solid geometry.
- Define the material and structural properties.
- Apply the required boundary conditions and loading.
- Generate a suitable finite element mesh.
- Determine the deformation of the beam.
- Determine the stress distribution in the beam.
- Compare the 3D FEA results with analytical and 1D FEA results.

---

## Analysis Methodology

The 3D beam analysis was carried out in ANSYS Mechanical using the
following workflow:

1. Create/import the 3D beam geometry.
2. Define the material properties.
3. Apply the required supports and loading.
4. Generate the finite element mesh.
5. Solve the structural analysis.
6. Post-process the stress and deformation results.
7. Compare the results with analytical calculations and the 1D FEA model.

---

## Model Setup

### Geometry

The beam was modelled using its actual three-dimensional geometry,
including its cross-sectional dimensions.

### Material

The material properties used in the analysis were defined according
to the selected beam material.

### Boundary Conditions

The required supports were applied to represent the specified
constraint conditions.

### Loading

The prescribed external force was applied at the specified location
on the beam.

---

## Meshing

A finite element mesh was generated over the 3D beam geometry.

The mesh was selected to provide an appropriate balance between
solution accuracy and computational cost.

### Mesh
![3D Beam with All Applications](3%20D%20Beam%20with%20all%20Applications.png)


---

## Boundary Conditions and Loading

The applied supports and loading conditions are shown below.
![Fixed Support](Fixed%20Support%20at%20Edge.png)

---

## Results

### Total Deformation

The total deformation obtained from the 3D finite element analysis is
shown below.

![3D Total Deformation](Total%20Deformation.gif)

### Equivalent Stress

The equivalent (von-Mises) stress distribution obtained from the
analysis is shown below.
![3D Equivalent Stress](Equivalent%20Stress.gif)

---

## Results Comparison

The 3D FEA results were compared with the analytical solution and
the results obtained using 1D beam elements.

| Parameter | Analytical | 1D FEA | 3D FEA |
|-----------|------------|---------|---------|
| Maximum Stress | 375 MPa | 372 MPa | 378 MPa |
| Maximum Deformation | 0.785 mm | 0.785 mm | 0.788 mm |

---

## Engineering Observations

The 3D solid-element model provides a detailed representation of the
beam's physical geometry and stress distribution.

The results were compared with the analytical solution and the 1D
beam-element model to evaluate the accuracy of the finite element
approaches.

Any difference between the analytical and FEA results may be
attributed to factors such as mesh discretization, element
formulation, loading representation and modelling assumptions.

---

## Conclusion

The beam was successfully analyzed using 3D solid elements in ANSYS
Mechanical.

The obtained stress and deformation results were compared with the
analytical solution and the 1D beam-element analysis. This comparison
demonstrates the application of finite element analysis for structural
beam problems and the importance of validating numerical results
against theoretical calculations.

---

## Software Used

- ANSYS Mechanical
- CAD software
- Microsoft Excel / Engineering calculations

---

## Skills Demonstrated

- Finite Element Analysis (FEA)
- Structural Analysis
- 3D Solid Element Modelling
- Meshing
- Boundary Condition Definition
- Stress Analysis
- Deformation Analysis
- FEA Post-processing
- Analytical Validation
