# Master 1 – Numerical Analysis (Fundamental Mathematics)

This repository contains a collection of practical projects (*Travaux Pratiques*) carried out during my first year of Master’s degree in **Fundamental Mathematics**.  
The focus is on **numerical methods for Partial Differential Equations (PDEs)**, with applications ranging from diffusion processes to nonlinear conservation laws.

---

## Contents

- **TP1 – Diffusion equation (sugar dissolution model)**  
  Implementation of numerical schemes to approximate the solution of the 1D heat equation, modeling the diffusion of sugar in water.  
  - Separation of variables and analytical solution.  
  - Explicit and implicit finite-difference schemes.  
  - Stability and convergence analysis.  

- **TP2 – Linear transport equation**  
  Study of the advection (transport) equation and its numerical resolution.  
  - Method of characteristics.  
  - Upwind / Rusanov schemes.  
  - Comparison of **dense vs sparse matrix** implementations for computational efficiency.  

- **TP3 – Burgers’ equation**  
  Exploration of nonlinear PDEs through Burgers’ equation.  
  - Shock formation and Rankine–Hugoniot condition.  
  - Numerical approximation with finite-volume methods.  
  - Illustration of nonlinear wave propagation.  

---

## Purpose

These projects illustrate how **numerical analysis** provides practical tools to study and approximate PDEs that model real-world phenomena such as **diffusion, transport, and nonlinear shocks**.

---

## Usage

Each TP is provided as a **Jupyter notebook** with explanations and visualizations.  
To run them, simply clone the repository and use:

```bash
jupyter notebook
