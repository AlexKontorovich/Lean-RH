# Riemann Hypothesis in Lean (with or without mathlib)

By Brandon Gomes and Alex Kontorovich
Department of Mathematics, Rutgers University

This repository contains the formalization of the Riemann Hypothesis (in terms of the Dirichlet eta function) in the Lean Interactive Theorem Prover.

The documents `basic`, `cauchy`, `complex`, `dirichlet_eta`, `exponential`, `riemann_hypothesis`, and `riemann_zeta` are standalone files not using mathlib. They assume certain properties of real and complex numbers, and certain facts about the real/complex logarithm and exponential functions.

The (equivalent) formulation of the Riemann hypothesis stated in `riemann_hypothesis` is: if 0<Re(s)<1 and DirichletEta(s)=0, then Re(s)=1/2.

We also give a file, `impl`, which is a witness that these properties can be proved within mathlib (including lemmata on real/complex log/exp functions as defined in mathlib).
