# Active-Gel Modeling of Non-Adhesive Cell Migration

## 🧬 Overview

This project focuses on the mathematical and computational modeling of **non-adhesive cell migration** using an active-gel continuum framework.

The model investigates how a spatial variation in friction can influence cell movement, with particular focus on **friction-gradient-driven migration (frictiotaxis)**.

The project combines mathematical modeling, nonlinear differential equations, non-dimensionalization, and numerical computation to develop a quantitative model of cell migration.

---

## 🎯 Objective

The primary objective of this project is to develop and computationally investigate a mathematical model describing cell migration driven by a spatial friction gradient.

The project aims to:

- Formulate a continuum active-gel model for non-adhesive cell migration.
- Represent the coupled dynamics of the cytoskeletal system mathematically.
- Derive the governing nonlinear differential equations.
- Apply appropriate non-dimensionalization to simplify the model.
- Solve the resulting boundary-value problem numerically.
- Analyze the effect of model parameters on cell migration.
- Compare computational results with published theoretical and experimental observations.
- Develop a reproducible Python-based computational pipeline.

---

## 🔬 Scientific Background

Cell migration is an important biological process involved in phenomena such as immune-cell trafficking, tissue organization, wound healing, and cancer metastasis.

Many models of cell migration emphasize adhesion between the cell and its surrounding substrate.

However, cells can also exhibit **non-adhesive migration**, where movement occurs without relying primarily on conventional focal adhesions.

This project investigates how a **gradient in friction** can contribute to directed cell migration.

The mathematical framework is based on an **active-gel continuum description**, which provides a way to represent the mechanical behavior and active dynamics of the cytoskeleton.

---

## 🧮 Mathematical Modeling

The model is formulated using coupled nonlinear differential equations representing the relevant physical and mechanical variables of the active-gel system.

The governing equations are analyzed and transformed into a suitable non-dimensional form.

The resulting mathematical problem is formulated as a **boundary-value problem (BVP)**.

The computational workflow can be summarized as:

Real-world biological problem

↓

Physical assumptions

↓

Continuum active-gel model

↓

Governing nonlinear PDEs/ODEs

↓

Non-dimensionalization

↓

Boundary conditions

↓

Numerical BVP formulation

↓

Python/SciPy implementation

↓

Numerical solution

↓

Parameter analysis

↓

Comparison with published results

---

## 💻 Computational Approach

The computational implementation is developed primarily in **Python**.

### Main tools

- Python
- NumPy
- SciPy
- SymPy
- Jupyter Notebook

### Numerical methods

The project involves:

- Non-dimensionalization
- Nonlinear differential equations
- Boundary-value problem formulation
- Numerical BVP solution
- Parameter analysis
- Computational benchmarking

---

## 📁 Repository Structure

```text
active-gel-cell-migration/
│
├── README.md
│
├── src/
│   ├── equations.py
│   ├── model.py
│   ├── solver.py
│   └── parameters.py
│
├── notebooks/
│   ├── 01_model_formulation.ipynb
│   ├── 02_nondimensionalization.ipynb
│   ├── 03_numerical_solution.ipynb
│   └── 04_results_analysis.ipynb
│
├── results/
│   ├── figures/
│   └── data/
│
├── tests/
│
├── requirements.txt
│
└── LICENSE#
Computational modeling of friction-gradient-driven non-adhesive cell migration using Python, nonlinear differential equations, and numerical BVP methods
