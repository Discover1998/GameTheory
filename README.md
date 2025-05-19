# GameTheory
**GameTheory: Nash Equilibrium RBAC &amp; ABAC Access Control**
This project combines Game Theory and Agent-Based Simulation to evaluate and optimize access control strategies using RBAC (Role-Based Access Control) and ABAC (Attribute-Based Access Control).
---
## Installation
To run the simulation, install the required libraries by executing the following command in your terminal, depending on your operating system:
- **Windows:**
  ```bash
  pip install -r libraries.txt

- **Linux / MacOS:**
  ```bash
  pip3 install -r libraries.txt
---
## How to run the simulations
- **To run the hybrid model**
  ```bash
  python hybrid.py
  
- **To run the pure abac model**
  ```bash
  python pure_abac.py
  
- **To run the pure rbac model**
  ```bash
  python pure_rbac.py

- **To generate breach rate benchmarks**
  ```bash
  python comparison.py

 <ins>On macOS/Linux, use python3 instead of python if needed.</ins>
---
## To simulate the environments
- **For ABAC:**
  <ins>Go in the ABAC Environment folder and follow the instructions in README.md file</ins>
- **For RBAC:**
  <ins>Go in the RBAC Environment folder and follow the instructions in README.md file</ins>

## Authors
***Najem Aldeen Abu Hamdah & Yazan Almoued***
