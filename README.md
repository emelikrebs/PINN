$\lambda$ Coupled Thermo-Mechanical PINN Solver $\lambda$(Physics-Informed Neural Networks for Coupled Multi-Physics Analysis)

This repository contains the software framework developed during a research internship at the Helmut-Schmidt-Universität, Germany, focusing on extending Physics-Informed Neural Networks (PINNs) to solve coupled multi-physics problems.
The project implements a continuous machine learning solution for simulations that traditionally require Finite Element Methods (FEM).

Objectives and Core Methodology
1. Problem Addressed: Modeling of Coupled Thermo-Mechanical Systems (steady-state), where the temperature field dictates the material's stiffness [$C(T)$].
2. Methodology: Development of a unified loss function that integrates the Governing Equations for Thermal Conduction (Laplace) and Mechanical Equilibrium (Piola-Kirchhoff).
3. Architecture: Fully connected PINN architecture using the tanh activation function, trained to simultaneously predict Displacement $u(x)$ and Temperature $T(x)$ fields.
