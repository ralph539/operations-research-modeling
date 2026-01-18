
# Recherche Opérationnelle – Travaux Pratiques (N7, 2A, S1)

Bienvenue dans le dépôt des Travaux Pratiques de Recherche Opérationnelle.
Ce projet regroupe des TPs sur la **programmation linéaire**, la **modélisation de problèmes d'optimisation** et l'utilisation du solveur **GLPK (GNU Linear Programming Kit)**.

Vous trouverez ici des modèles, des instances, des notebooks et les sources du solveur pour expérimenter et analyser différents problèmes d'optimisation.


## 📁 Structure du projet

```
TP/
├── TP1/
│   └── solveurGLPK/
│       └── sources/
│           ├── glpk-5.0.tar.gz        # Archive source GLPK
│           └── glpk-5.0/              # Code source GLPK extrait
│               ├── doc/               # Documentation GLPK
│               ├── examples/          # Exemples de problèmes
│               ├── src/               # Code source du solveur
│               └── ...
├── TP2-TP3/
│   ├── KnapSack_Optimization/         # TP2 : Modélisation & résolution du sac à dos
│   │   ├── NotebookTP2.ipynb          # Notebook Jupyter TP2
│   │   └── InstancesKnapSack/         # Instances du problème
│   └── SAT_Modeling_Advanced/         # TP3 : Modélisation avancée SAT/PLNE
│       ├── TP3_skeleton.ipynb         # Notebook Jupyter TP3
│       └── InstancesKnapSack/         # Instances pour SAT/PLNE
└── TPRO/
    └── ...                            # Autres modèles et données
```



## 🎯 Objectifs pédagogiques

- Comprendre les bases de la **programmation linéaire**
- Savoir utiliser et compiler un solveur industriel (**GLPK**)
- Modéliser et résoudre des problèmes d’optimisation (PL, PLNE, SAT)
- Expérimenter sur des instances réelles et synthétiques (KnapSack, SAT, etc.)
- Faire le lien entre théorie (formulation) et pratique (résolution, analyse)


## 🛠️ Prérequis
- Environnement Linux/Unix (recommandé)
- GCC / Make
- Dépendances GLPK (outils de compilation standards)


## 🚀 Compilation & utilisation

Pour compiler GLPK :

```bash
cd TP/TP1/solveurGLPK/sources/glpk-5.0
./configure
make
sudo make install
```

Pour les TPs Jupyter :
- TP2 (sac à dos) : `TP2-TP3/KnapSack_Optimization/NotebookTP2.ipynb`
- TP3 (SAT/PLNE) : `TP2-TP3/SAT_Modeling_Advanced/TP3_skeleton.ipynb`

Ouvrez les notebooks dans VS Code ou JupyterLab pour explorer les modèles et les analyses.

## 👥 Auteurs
- Ralph Khairallah ([ralphkhairallah200@gmail.com](mailto:ralphkhairallah200@gmail.com))
- Baptiste Rembert

## 📄 Licence
Ce dépôt contient des sources open source (GLPK) et des travaux académiques. Voir les fichiers COPYING/README pour plus de détails.
