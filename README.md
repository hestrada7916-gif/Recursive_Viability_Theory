# Recursive Viability Theory

**Recursive Viability Theory (RVT)** is a research framework for modeling adaptive persistence, collapse, and recovery through the preservation or contraction of reachable future-state accessibility under recursive constraint.

This repository contains the Phase I formalization artifacts for the **Viable Transformation Flow Architecture (VTFA)**, including canonical primitives, observables, phase definitions, governance rules, and empirical implementation targets.

---

## Core Thesis

Adaptive systems persist by preserving survivably reachable futures.

Collapse begins when reachable adaptive futures contract.

Irreversible collapse occurs when reachable future accessibility is exhausted.

In compressed form:

```text
Persistence = recoverable differentiated accessibility.
```

---

## Primary Objects

### Reachable Future-State Set

```math
\mathcal R^+(x,t;T)
```

The set of survivably reachable future states from state `x` at time `t` over horizon `T`.

### Reachable Future-State Measure

```math
V^+(x,t;T)=\mu(\mathcal R^+(x,t;T))
```

A measure of accessible future-state structure.

### Survivability Capacity

```math
\mathcal P_{\mathrm{surv}}
=
\frac{\mathcal A_{\mathrm{dir}}}{\mathcal B_{\mathrm{rec}}}
```

Survivability depends on retained directional asymmetry relative to recursive constraint burden.

### Coordination Invariant

```math
\Xi(E,\Theta)=\frac{E(1-E)}{1+\Theta}
```

A minimal coordinate realization of survivable differentiated coordination under recursive burden.

---

## Operational Survivability Law

Adaptive persistence requires retained directional asymmetry to exceed recursive constraint burden sufficiently to preserve survivably reachable future accessibility.

```math
\mathcal P_{\mathrm{surv}} > \xi_c
```

where `ξ_c > 0` is the minimum survivable viability threshold.

---

## Coordination Definition

Coordination is recoverable differentiated compatibility under recursive burden.

This means coordination does **not** require symmetry, uniformity, equilibrium, or synchronization. It requires compatibility among differentiated structures that remains preservable or recoverable under accumulated constraint.

---

## Phase I Research Goals

Phase I focuses on internal consistency, admissible dynamics, and falsifiable accessibility signatures.

Current goals:

1. Lock admissible reachability formalism.
2. Define generalized accessibility measure classes.
3. Formalize accessibility evolution laws.
4. Define metastable plateau geometry.
5. Build empirical accessibility estimators.
6. Construct falsifiable validation kernels.
7. Freeze Phase I notation and registry governance.

---

## Phase Taxonomy

### Viable

Accessible futures remain broad and recoverable.

### Compressed

Reachable future accessibility is contracting, but recovery remains possible.

### Critical

Collapse alignment becomes persistent and recovery becomes difficult.

### Collapsed

Viable adaptive transitions are exhausted or inaccessible within the tested horizon.

### Recovering

Accessibility reopens after compression.

---

## Repository Structure

Planned structure:

```text
Recursive-Viability-Theory/
│
├── README.md
├── registry/
│   └── vtfa_registry_v1.json
│
├── theory/
│   ├── admissible_reachability_kernel.tex
│   ├── operational_survivability_law.tex
│   ├── metastable_coordination_principle.tex
│   └── accessibility_evolution_law.tex
│
├── notebooks/
│   ├── 00_registry_validation.ipynb
│   ├── 01A_synthetic_accessibility_geometry.ipynb
│   ├── 01B_observable_estimation.ipynb
│   └── 01C_phase_detection.ipynb
│
├── src/
│   ├── registry_loader.py
│   ├── validators.py
│   ├── synthetic_systems.py
│   ├── accessibility_metrics.py
│   └── phase_detection.py
│
├── results/
│   ├── json/
│   ├── figures/
│   └── tables/
│
└── docs/
    ├── glossary.md
    ├── notation_guide.md
    └── architecture_overview.md
```

The repository will begin minimally and expand only as objects become operational.

---

## Governance Rules

No new theoretical object enters Phase I unless it is assigned:

- symbol,
- name,
- object type,
- dependency role,
- estimator status,
- notebook ownership,
- JSON serialization field.

Short form:

```text
If it cannot be serialized, it is not yet operational.
```

---

## Scope

Recursive Viability Theory is:

- geometric,
- substrate-invariant,
- non-deterministic,
- accessibility-centered,
- empirically extensible.

It is not currently:

- a universal predictive engine,
- a medical diagnostic system,
- a metaphysical ontology,
- or a replacement for domain science.

---

## One-Sentence Lock

Recursive Viability Theory models adaptive persistence through preservation of survivably reachable future accessibility under recursive constraint and admissible viability dynamics.
