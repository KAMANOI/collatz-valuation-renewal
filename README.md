# Valuation Renewal, Finite Residue Connectivity, and the Orbitwise Gap in Collatz Dynamics

**2026**

Develops a structural analysis of the Collatz map through renewal theory, 2-adic symbolic dynamics, and finite residue control. Establishes three independent pillars and identifies the precise orbitwise gap that remains open.

> This repository does not claim a proof of the Collatz conjecture.

---

## Overview

The central result is that divergence of a Collatz orbit must simultaneously satisfy three conditions: the empirical valuation average falls below log₂ 3, valuation complexity is unbounded, and the orbit sustains orbitwise arithmetic decorrelation that escapes the finite-information renewal structure.

The three pillars:

- **Theorem AV** (Average Valuation): Under the Haar/renewal population model, the average odd-step valuation equals 2 > log₂ 3 — giving negative population Lyapunov drift
- **Theorem NRC** (Non-trivial Residue Connectivity): The mod-2^K Type A residue transition graph is strongly connected for all K ≥ 3
- **Theorem BVC** (Bounded Valuation Complexity): Bounded valuation complexity implies eventual finite symbolic periodicity

---

## Main Results

### Proved (Rigorous)

| Result | Method | Status |
|--------|--------|--------|
| Theorem AV: population drift negative (avg valuation = 2 > log₂ 3) | Renewal / Haar model | ✓ proved |
| Theorem NRC: strong connectivity of mod-2^K residue graph (K ≥ 3) | Graph theory / congruence | ✓ proved |
| Theorem BVC: bounded complexity → eventual periodicity | Symbolic dynamics | ✓ proved |

### Conditional

| Result | Condition | Status |
|--------|-----------|--------|
| Theorem EL (Ergodic Lift) | Finite-level Doeblin condition | conditional |

### Open Problems

| Problem | Label |
|---------|-------|
| lim inf (1/M) Σvₜ > log₂ 3 (orbitwise) | OP4-min |
| (1/M) Σkₜ → 2 (orbitwise mean) | OP4-mean |
| Orbitwise decorrelation of parity (Λ_C) | OP4-Chowla |
| Doeblin condition for the renewal kernel | Doeblin |

---

## Structure

```
§1   Introduction
§2   Type A / Type B cycle structure and one-cycle decomposition
§3   Population drift (Theorem AV)                     ✓
§4   Finite residue connectivity (Theorem NRC)         ✓
§5   Bounded valuation complexity (Theorem BVC)        ✓
§6   The orbitwise gap and open problems               open
§7   Conclusion
```

---

## Open Problems

- OP4-min: individual orbit valuation average above log₂ 3
- OP4-Chowla: orbitwise decorrelation of the parity sequence (parity barrier)
- Doeblin condition: finite-level mixing for the renewal kernel

---

## Repository Structure

```
collatz-valuation-renewal/
├── README.md
├── paper/
│   └── valuation_renewal_finite_residue_orbitwise_gap.pdf
└── LICENSE
```

---

## Related Work

This paper is part of a series on Collatz dynamics:

- [collatz-act1](https://github.com/KAMANOI/collatz-act1) — Foundational paper: prime survival dynamics and Chen-type theorem (v11)
- [collatz-renewal-structure](https://github.com/KAMANOI/collatz-renewal-structure) — Paper A: exact operator structure and finite information memory
- [collatz-finite-mixing-geometry](https://github.com/KAMANOI/collatz-finite-mixing-geometry) — Paper B: finite-level mixing geometry
- [collatz-spectral-amplification](https://github.com/KAMANOI/collatz-spectral-amplification) — Paper C: spectral amplification
- [collatz-scale-coherence](https://github.com/KAMANOI/collatz-scale-coherence) — Paper D: scale-coherence rigidity
- [collatz-valuation-renewal](https://github.com/KAMANOI/collatz-valuation-renewal) — Valuation renewal, finite residue connectivity, and orbitwise gap
- [collatz-residual-core](https://github.com/KAMANOI/collatz-residual-core) — The residual core: structural decomposition
- [collatz-congruence-synchronization](https://github.com/KAMANOI/collatz-congruence-synchronization) — Paper H: nested congruence constraints on synchronization
- [collatz-record-renewal](https://github.com/KAMANOI/collatz-record-renewal) — Paper N: record renewal compatibility
- [collatz-hensel-escape](https://github.com/KAMANOI/collatz-hensel-escape) — Paper O: Hensel memory and 2-adic escape target
- [collatz-hensel-scarcity](https://github.com/KAMANOI/collatz-hensel-scarcity) — Paper T: Hensel conditional scarcity and telescoping contradiction
- [collatz-prefix-counting](https://github.com/KAMANOI/collatz-prefix-counting) — Paper V: direct prefix counting and synchronization collapse
- [collatz-first-passage](https://github.com/KAMANOI/collatz-first-passage) — Paper W: first-passage obstruction (closes series A–V)
- [collatz-series-summary](https://github.com/KAMANOI/collatz-series-summary) — Series summary: research program on Collatz synchronization dynamics
- [collatz-prime-survival](https://github.com/KAMANOI/collatz-prime-survival) — Paper X v20: prime survival in affine Collatz dynamics

---

## Author

Hiroki Kamanoi
hirokikamanoi@gmail.com
2026
