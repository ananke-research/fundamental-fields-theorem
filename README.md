# Fundamental Fields Theorem

This repository contains the **Fundamental Fields Theorem (FFT)**, a structural
classification result concerning **classical fields under closure**.

The theorem establishes that **gravity is the unique classical field capable of closure**
when finite conserved field energy, covariance, and exhaustion of functional freedom under
symmetry are required.

The result is deductive, parameter-free, and independent of phenomenology.  
No actions, scaling laws, or regime behaviour are derived here. Those occur strictly
downstream.

---

## Scope and purpose

The purpose of the Fundamental Fields Theorem is **classification**, not modelling.

It answers the upstream question:

> *Which classical fields are admissible in principle once closure is required?*

Closure is defined as the ability of a field to self-regulate with finite conserved norm
under symmetry, without external bookkeeping or additional degrees of freedom.

---

## Core result

Under the requirements of:

- classical covariance,
- finite conserved quadratic field norm,
- exhaustion of functional degrees of freedom under symmetry,

the Fundamental Fields Theorem establishes that:

- **gravity alone closes** as a classical field;
- all other classical fields fail closure under symmetry reduction;
- gravity’s admissibility is structural, not contingent.

This result is logically prior to any statement about gravitational dynamics or actions.

---

## What this theorem does not do

This work does **not**:

- derive gravitational field equations;
- classify vacuum or non-vacuum regimes;
- introduce residual degrees of freedom;
- address galaxy dynamics or cosmology;
- engage phenomenological data.

Those questions are addressed downstream in the Ananke framework.

---

## Repository structure

- [`paper/`](paper/)  
  Canonical paper artefacts.  
  The Zenodo record is the **version of record**; the PDF here is a mirror only.
  Editable source files are located in [`paper/source/`](paper/source/).

- [`pages/`](pages/)  
  Short technical pages that mirror the paper’s logical structure.
  These pages restate results for clarity and navigation and introduce no new claims.

---

## Pages overview

The `pages/` directory mirrors the paper’s section structure:

- [`pages/00-overview.md`](pages/00-overview.md) — overview  
- [`pages/01-problem-statement.md`](pages/01-problem-statement.md) — problem statement  
- [`pages/02-definitions-of-closure.md`](pages/02-definitions-of-closure.md) — definitions of closure  
- [`pages/03-axioms-and-admissibility.md`](pages/03-axioms-and-admissibility.md) — axioms and admissibility  
- [`pages/04-exhaustion-of-functional-freedom.md`](pages/04-exhaustion-of-functional-freedom.md) — exhaustion of functional freedom  
- [`pages/05-classification-of-classical-fields.md`](pages/05-classification-of-classical-fields.md) — classification of classical fields  
- [`pages/06-why-gravity-is-unique.md`](pages/06-why-gravity-is-unique.md) — gravity’s uniqueness  
- [`pages/07-domain-of-validity-and-falsification.md`](pages/07-domain-of-validity-and-falsification.md) — domain of validity and falsification  

---

## Relation to other repositories

This repository is part of a logically ordered framework:

- [`fundamental-fields-theorem`](https://github.com/ananke-research/fundamental-fields-theorem) *(this repository)*  
  Establishes gravity as the unique classical field capable of closure.

- [`ananke-theorem`](https://github.com/ananke-research/ananke-theorem)  
  Classifies the admissible closed gravitational field structure and unique action.

- [`phenomenological-consequences-of-ananke`](https://github.com/ananke-research/phenomenological-consequences-of-ananke)  
  Derives the observable galactic and cosmological scaling relations implied by that
  structure.

- [`structural-diagnostics-of-gravitational-closure`](https://github.com/ananke-research/structural-diagnostics-of-gravitational-closure)  
  Develops falsification criteria and diagnostic interpretation.

Each repository has a distinct logical role and should be cited independently.

---

## Citation

If you use or reference this work, cite the Zenodo record listed in
[`CITATION.cff`](CITATION.cff).

The Zenodo record is the canonical version of record.

---

## License

This work is released under the **Creative Commons Attribution 4.0 International (CC BY 4.0)** license.

See [`LICENSE`](LICENSE) for full terms.
