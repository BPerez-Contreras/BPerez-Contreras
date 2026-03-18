# Benjamín Felipe Pérez Contreras

**Researcher | Information Geometry & Statistical Learning Theory**

[![ORCID](https://img.shields.io/badge/ORCID-0009--0008--3929--8680-A6CE39?logo=orcid&logoColor=white)](https://orcid.org/0009-0008-3929-8680)
[![ResearchGate](https://img.shields.io/badge/ResearchGate-Profile-00CCBB?logo=researchgate&logoColor=white)](https://www.researchgate.net/profile/Benjamin-Perez-Contreras)
[![Zenodo](https://img.shields.io/badge/Zenodo-Publications-0070C0?logo=zenodo&logoColor=white)](https://zenodo.org/search?q=metadata.creators.person_or_org.name%3A%22P%C3%A9rez%20Contreras%2C%20Benjam%C3%ADn%20Felipe%22&l=list&p=1&s=10&sort=mostviewed)

---

## Research

I work on the geometry of learnability: when does local neighborhood structure determine
global predictability, and what are the precise limits of that determination?

My main object is the **Local Class Transition Tensor** T_{cc'j}, a functional on joint
distributions that is uniquely characterized by four axioms (normalization, linearity,
locality, SK-equivariance). This uniqueness result grounds a Riemannian structure on
the probability simplex whose geometric invariants — curvature, geodesics, spectral
properties — serve as domain-independent diagnostics of learnability.

Current directions:

- Spectral properties of k-NN graphs under label-guided geometric flows
- Connections between Ricci flow singularities and computational phase transitions
  in random k-SAT
- Combinatorial analogues of APS index theory on Hamming graphs

---

## Selected Results

**Exact identity (algebraic).**
For k=1, the semantic tolerance equals the leave-one-out accuracy of 1-NN exactly:
tau*(k=1) = Acc_LOO_1-NN. This is a consequence of the tensor axioms, not an
empirical observation.

**Uniqueness theorem.**
The transition tensor T_{cc'j} is the unique functional satisfying normalization,
linearity, locality, and equivariance under label permutations. Proved via
Stone (1977) for the continuous limit.

**Nonlinear curvature evolution.**
Under label-guided discrete Ricci flow on k-NN graphs, the Forman-inspired edge
curvature satisfies:

  d(kappa)/dt = gamma_1 * kappa * d_avg + gamma_2 * L_w[kappa] + gamma_3 * C_e * kappa

with gamma_3 = 2*eta derived from a discrete BBGKY closure. Validated at R^2 = 0.96
across 50 datasets.

**Bimodal convergence.**
Under the same flow with tau* > 0.88, all inter-class edges are expelled in finite
time and intra-class curvature converges. Proved via Gronwall inequality and a
Lyapunov functional. The threshold tau* = 0.89 is derived, not fitted, via
neighborhood correlation rho-bar = k*C/n correcting a conservative union bound.

**Spectral gap.**
The solution graph of random 3-SAT at criticality decomposes into path graphs P_N
(~80% of connected components). P5 is the unique path graph with spectrum in Z[phi],
with Fiedler value lambda_2 = phi^{-2} = 2 - phi exact to six decimal places.
This yields a closed-form expression for the Semantic Boltzmann Constant:
R_S = 2 / (18 - 7*lambda_2).

---

## Open Problems I Am Working On

1. Does the Fisher-Rao metric on the 3-SAT solution manifold evolve under clause
   density as a Ricci flow? The empirical identity R(alpha) = -(2/k) * d(ln N_SAT)/d(alpha)
   suggests yes; a formal derivation from belief propagation equations is open.

2. Do the spectral modes of the neck-pinch singularity in that flow generate a
   harmonic Maass form via the APS eta invariant? The structure is consistent with
   Zagier (1975) and Bringmann-Ono (2006); verification requires expertise in
   spectral theory of degenerating manifolds.

3. Can the Allen-Cahn nucleation barrier (beta_AC = 7.49 vs beta_circuit = 0.262)
   be converted into a formal circuit lower bound within ZFC?

---

## Publications

Full record on Zenodo:
https://zenodo.org/search?q=metadata.creators.person_or_org.name%3A%22P%C3%A9rez%20Contreras%2C%20Benjam%C3%ADn%20Felipe%22&l=list&p=1&s=10&sort=mostviewed

---

## Contact

Open to discussion and collaboration, particularly on the three open problems above.

benjamin.perezc.contact@gmail.com
