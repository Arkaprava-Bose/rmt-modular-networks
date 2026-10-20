# Stability of Modular Community Networks with Random Module Sizes

Spectral study of ecological community matrices whose interaction network is organised into modules, with module sizes drawn from a distribution. It generalises the two-module construction of Grilli, Rogers and Allesina (2016) to an arbitrary number of modules.

---

## Model

A community of *S* species is described by the community matrix

```math
M = W \circ K, \qquad M_{ii} = 0
```

where *W* holds the random interaction strengths and *K* is the adjacency matrix of a graph split into *n*<sub>c</sub> modules of relative sizes **α**, with prescribed overall connectance *C* and modularity *Q*. Stability is governed by the rightmost eigenvalue of *M*.

---

## Approach

- Decomposition *M* = *A* + *B* into a deterministic modular part and a random part.
- Cavity method for the bulk of the spectrum.
- Direct numerical simulations of the spectrum of *M*.

---

## Status

Done:
- Construction of the modular community matrix for general *n*<sub>c</sub> and module sizes.
- Spectral prediction for equal module sizes, verified numerically.

Ongoing:
- Extension to unequal module sizes drawn from a distribution.
- Stability statistics over the ensemble.

---

## References

- J. Grilli, T. Rogers, S. Allesina, *Modularity and stability in ecological communities*, Nat. Commun. **7**, 12031 (2016).
- R. M. May, *Will a large complex system be stable?*, Nature **238**, 413 (1972).
- S. Allesina, S. Tang, *Stability criteria for complex ecosystems*, Nature **483**, 205 (2012).

---

## Author

Arkaprava Bose, IISER Kolkata

Advisor: Anandamohan Ghosh, IISER Kolkata
