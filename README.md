# Glass Container Industry Problem – New Furnace Installation (GCIP-NF)

This repository contains the mathematical model and algorithm implementation for the furnace installation problem in the glass container industry, based on the industrial case study from Minas Gerais, Brazil (2019).

## 📋 Project Description
The **GCIP-NF** is a Mixed-Integer Linear Programming (MILP) model designed to simultaneously optimize:
1. The melting capacity of the new furnace ($KF$).
2. The selection and installation of forming machines ($Y_m$).
3. The production planning required to meet annual demand.

The primary objective is to minimize total capital expenditure (CAPEX) and operational costs related to thermal and production infrastructure.



## 💻 Technologies and Tools
The project was developed in **Python** using the following optimization ecosystem:
- **Pyomo**: Mathematical modeling framework.
- **Highs Solver**: High-performance solver for MILP problems.
- **Pandas/NumPy**: For data manipulation and instance parameter handling.

## 🚀 How to Run
The code is provided as a Jupyter Notebook (`.ipynb`), which can be executed locally or via Google Colab.

### 1. Installation
To run the optimization, you need to install Pyomo and the HiGHS solver. In a terminal or notebook cell, run:
```bash
pip install pyomo
apt-get install -y -qq highs-solver
