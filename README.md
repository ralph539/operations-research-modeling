📐 Optimization & Linear Programming – GLPK Solver TP
This repository contains a university practical assignment (TP) focused on **linear programming and optimization**, using the **GLPK (GNU Linear Programming Kit)** solver.

The project explores modeling, solving, and experimenting with linear optimization problems using GLPK, including source compilation and solver execution.

🔍 Project Structure
TP/
├── TP1/
│   └── solveurGLPK/
│       └── sources/
│           ├── glpk-5.0.tar.gz        → Original GLPK source archive
│           └── glpk-5.0/              → Extracted GLPK source code
│               ├── doc/               → GLPK documentation (PDF, LaTeX)
│               ├── examples/          → Example optimization problems
│               ├── src/               → Core GLPK solver source code
│               ├── configure / Makefile tools
│               └── build scripts
├── TP2-TP3/
│   ├── KnapSack_Optimization/         → (ex-Sujet_2_REMBERT_Baptiste_KHAIRALLAH_Ralph) TP2: KnapSack problem modeling & solving
│   │   ├── NotebookTP2.ipynb          → Jupyter notebook for TP2
│   │   └── InstancesKnapSack/         → KnapSack problem instances
│   └── SAT_Modeling_Advanced/         → (ex-Sujet_3_REMBERT_Baptiste_KHAIRALLAH_Ralph) TP3: Advanced SAT/PLNE modeling
│       ├── TP3_skeleton.ipynb         → Jupyter notebook for TP3
│       └── InstancesKnapSack/         → KnapSack problem instances for SAT/PLNE
└── TPRO/
    └── ...                            → Other optimization models and data


🧠 Project Objectives
The goals of this repository are to:

- Understand the fundamentals of **linear programming**
- Learn how to **use and compile an industrial-grade solver (GLPK)**
- Model and solve optimization problems (LP, PLNE, SAT)
- Experiment with real and synthetic instances (KnapSack, SAT, etc.)
- Bridge theory (formulation) with practical solver execution and analysis

🛠️ Requirements
- Linux / Unix environment (recommended)
- GCC / Make
- GLPK dependencies (standard build tools)

🧪 Build & Usage
From the GLPK source directory:

```bash
cd TP/TP1/solveurGLPK/sources/glpk-5.0
./configure
make
sudo make install
```

For TP2 (KnapSack) and TP3 (SAT/PLNE), open the corresponding Jupyter notebooks in the renamed folders:

- TP2: `TP2-TP3/KnapSack_Optimization/NotebookTP2.ipynb`
- TP3: `TP2-TP3/SAT_Modeling_Advanced/TP3_skeleton.ipynb`
