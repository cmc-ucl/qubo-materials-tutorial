# QUBO Materials Tutorial

A hands-on workshop introducing how materials-science optimisation problems can be formulated and solved as QUBO (Quadratic Unconstrained Binary Optimisation) problems.

The tutorial is aimed primarily at researchers and students with a background in:
- quantum computing
- quantum annealing
- optimisation
- Ising/QUBO models

No prior experience in computational materials science is assumed.

---

# Overview

This tutorial introduces:

- binary optimisation and QUBO models
- constraints through penalty terms
- graph-based formulations
- classical simulated annealing with `neal`
- mapping simple atomistic materials problems onto QUBO formulations

The main running example is vacancies in graphene:
- building a graphene model
- constructing adjacency matrices
- defining vacancy variables
- enforcing fixed vacancy concentrations
- adding interaction terms
- solving the resulting QUBO

The tutorial also discusses:
- periodic boundary conditions
- supercells
- defect interactions
- extensions to dopants and alloys

---

# Contents

The notebook covers:

1. QUBO fundamentals
2. Graph partitioning example
3. Constraint construction
4. Classical annealing with `neal`
5. Vacancies in graphene
6. Vacancy interactions
7. Visualising periodic systems
8. Optional challenge exercises

---

# Running the tutorial

## Recommended: Google Colab

The notebook is designed to run directly in Google Colab.

1. Open the notebook in Colab
2. Save your own copy:
   File → Save a copy in Drive
3. Run the setup cells at the top of the notebook
4. Execute cells sequentially

The notebook installs required packages automatically.

No quantum hardware access is required.

---

# Local installation

The tutorial can also be run locally using Python 3.

Recommended packages:

pip install pymatgen dimod dwave-neal networkx matplotlib ase

---

# Main dependencies

- pymatgen
- ase
- dimod
- dwave-neal
- networkx
- matplotlib
- numpy

---

# Workshop exercises

The notebook includes exercises on:
- constraint construction
- graph interpretation
- vacancy optimisation
- neighbour interactions
- vacancy clustering
- sampler behaviour
- QUBO → Ising conversion

Most exercises are designed to be completed by modifying small sections of existing code.

---

# Educational goals

By the end of the tutorial, participants should understand how to:

materials problem
→ binary variables
→ interaction model
→ QUBO formulation
→ sampler/annealer
→ candidate atomic configurations

---

# Notes

The notebook primarily uses the classical simulated annealing sampler `neal`.

Sections discussing quantum annealers and D-Wave workflows are included for conceptual illustration and optional extension.

---

# License

This tutorial is intended for educational and research use.
