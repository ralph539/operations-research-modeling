

# 📐 Polytope Studio: Optimization & Modeling

This repository serves as a comprehensive workbench for **Operations Research** and **Combinatorial Optimization**. It contains custom implementations of linear programming models, a manually compiled build of the **GLPK (GNU Linear Programming Kit)** solver, and algorithmic analyses of NP-hard problems (Knapsack, SAT).

The project focuses on bridging the gap between theoretical mathematical formulation and practical solver performance.

## 🧠 Core Competencies

* **Linear Programming (LP):** Modeling complex constraints for industrial problems (logistics, production planning).
* **Integer Linear Programming (MILP):** Solving discrete combinatorial challenges.
* **Solver Architecture:** Building and interfacing with industrial-grade solvers (GLPK).
* **Complexity Analysis:** Benchmarking heuristics versus exact methods.

## 📁 Project Architecture

```text
.
├── glpk-core/               # GLPK 5.0 source code, build scripts, and local executables
│   ├── sources/             # Raw C source code for the solver
│   └── executables/         # Compiled binaries (glpsol)
│
├── linear-programming-models/ # AMPL/GMPL models for continuous optimization
│   ├── e-commerce/          # Supply chain optimization models
│   ├── production/          # Multi-constraint production planning
│   └── reports/             # Technical analysis (LP_Solver_Report.pdf)
│
├── discrete-optimization/   # Jupyter Notebooks for combinatorial problems
│   ├── knapsack/            # Knapsack Problem: Branch & Bound vs Heuristics
│   │   ├── Knapsack_Analysis.ipynb
│   │   └── instances/       # Benchmarking data (correlated/uncorrelated)
│   │
│   └── sat-logic/           # Boolean Satisfiability (SAT) & Logic constraints
│       ├── SAT_Solver_Modeling.ipynb
│       └── ...
│
└── README.md
```

---

## 🚀 Getting Started

### 1. Building the Environment (Linux/Unix)
This project uses a local build of GLPK to ensure version consistency. To compile the solver core:

```bash
cd glpk-core/sources/glpk-5.0
./configure
make
sudo make install
```

### 2. Running Optimization Models
The linear programming models can be solved using the standalone glpsol utility:

```bash
glpsol --math linear-programming-models/production/ModelCiment.mod
```

### 3. Interactive Analysis
The discrete optimization algorithms are implemented in Python/Jupyter for easier visualization of convergence and performance.

- Knapsack Analysis: Launch `discrete-optimization/knapsack/Knapsack_Analysis.ipynb`
- SAT Logic: Launch `discrete-optimization/sat-logic/SAT_Solver_Modeling.ipynb`

---

## 📊 Technical Highlights

### Knapsack Problem
Implemented multiple approaches to solve large-scale instances:

- Greedy Heuristics: Fast approximations based on value/weight density.
- Dynamic Programming: Exact solutions for bounded integer weights.
- Branch and Bound: Tree search implementation for optimal solutions.

### SAT & Logic
- Modeled complex logic puzzles as Integer Linear Programs.
- Transformed Boolean clauses into algebraic inequalities for solver processing.

---

## 👤 Author
Ralph Khairallah

Optimization Modeling & Software Engineering
