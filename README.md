

# 📐 Operations Research – Practical Assignments (N7, 2A, S1)

This repository contains practical assignments for Operations Research, focusing on **linear programming**, **optimization modeling**, and the use of the **GLPK (GNU Linear Programming Kit)** solver.

You will find models, data instances, Jupyter notebooks, and solver sources to experiment with and analyze various optimization problems.

---

## 📁 Repository Structure

```
TP/
├── TP1/
│   └── solveurGLPK/
│       └── sources/
│           ├── glpk-5.0.tar.gz        # GLPK source archive
│           └── glpk-5.0/              # Extracted GLPK source code
│               ├── doc/               # GLPK documentation
│               ├── examples/          # Example optimization problems
│               ├── src/               # Solver source code
│               └── ...
├── TP2-TP3/
│   ├── KnapSack_Optimization/         # TP2: Knapsack modeling & solving
│   │   ├── NotebookTP2.ipynb          # Jupyter notebook for TP2
│   │   └── InstancesKnapSack/         # Knapsack problem instances
│   └── SAT_Modeling_Advanced/         # TP3: Advanced SAT/ILP modeling
│       ├── TP3_skeleton.ipynb         # Jupyter notebook for TP3
│       └── InstancesKnapSack/         # Instances for SAT/ILP
└── TPRO/
    └── ...                            # Other models and data
```

---

## 🎯 Project Objectives

- Understand the basics of **linear programming**
- Learn to use and compile an industrial solver (**GLPK**)
- Model and solve optimization problems (LP, ILP, SAT)
- Experiment with real and synthetic instances (Knapsack, SAT, etc.)
- Bridge theory (formulation) and practice (solving, analysis)

---

## 🛠️ Requirements
- Linux/Unix environment (recommended)
- GCC / Make
- GLPK dependencies (standard build tools)

---

## 🚀 Build & Usage

To build GLPK:

```bash
cd TP/TP1/solveurGLPK/sources/glpk-5.0
./configure
make
sudo make install
```

For the Jupyter notebooks:
- TP2 (Knapsack): `TP2-TP3/KnapSack_Optimization/NotebookTP2.ipynb`
- TP3 (SAT/ILP): `TP2-TP3/SAT_Modeling_Advanced/TP3_skeleton.ipynb`

Open the notebooks in VS Code or JupyterLab to explore the models and analyses.

---

## 👥 Authors
- Ralph Khairallah ([ralphkhairallah200@gmail.com](mailto:ralphkhairallah200@gmail.com))
- Baptiste Rembert

---

## 📄 License
This repository contains open source (GLPK) and academic work. See COPYING/README files for details.
