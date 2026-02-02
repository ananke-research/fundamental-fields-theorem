# Fundamental Fields Theorem (FFT)

This repository contains the **Fundamental Fields Theorem (FFT)**, an upstream structural
classification result for classical interaction fields. The theorem addresses a logically
prior question to dynamics, modelling, or phenomenology:

**Which classical interaction fields can be fundamental in principle?**

The FFT establishes conservative criteria for fundamentality based on classical covariance
and self-contained conservation (closure), and applies them eliminatively to candidate
classes of classical fields.

The result is deductive and parameter-free. It introduces no field equations, no action,
no phenomenological modelling, and no empirical tuning. Its conclusions follow solely from
structural admissibility requirements.

---

## Core result

Under the minimal requirements of classical covariance and self-contained conservation
in closure regimes:

1. **Closure as a classificatory criterion:**  
   A fundamental classical interaction field must regulate its own conserved quantities
   without reliance on independent charge sectors, phenomenological prescriptions, or
   external bookkeeping, and must exhaust its functional freedom under sufficient symmetry.

2. **Eliminative classification:**  
   Gauge-type interaction fields, matter fields, and composite or effective descriptions
   necessarily fail closure in the stated sense and are therefore structurally open.

3. **Uniqueness of gravity:**  
   In the classical domain, the only interaction field capable of closure is gravity.
   Gravity is uniquely admissible as a fundamental classical interaction field; all
   non-gravitational interaction fields are necessarily open.

The theorem is classificatory rather than dynamical. It does not modify gravity, derive
its equations of motion, or assume any specific action.

---

## Repository structure

- `paper/` — canonical paper artefacts (PDF mirror and editable source). The Zenodo record
  is the version of record for citation purposes.
- `pages/` — short technical pages following the paper’s logical development; no new
  claims appear here.

---

## How to read

- Start with `pages/00-overview.md` for orientation.
- See `pages/05-classification-of-classical-fields.md` for the eliminative analysis.
- See `pages/06-why-gravity-is-unique.md` for the identification result.
- See `pages/07-domain-of-validity-and-falsification.md` for scope and limits.
- See `pages/papers.md` for the Zenodo record, DOI, and PDF mirror.

---

## Relation to other repositories

This repository sits upstream within a larger logically ordered framework:

- `fundamental-fields-theorem` — establishes which classical interaction field can close.
- `ananke-theorem` — determines the admissible internal structure of gravity under closure.
- `phenomenological-consequences-of-ananke` — derives regime-dependent scaling laws implied
  by the classified structure.
- `structural-diagnostics-of-gravitational-closure` — develops diagnostic and falsification
  criteria implied by closure.

Each paper is housed in a separate repository and should be cited independently.

---

## Citation

If you use or reference this work, cite the Zenodo record listed in `pages/papers.md`.
Machine-readable citation metadata is provided in `CITATION.cff` at the repository root.

The Fundamental Fields Theorem is complete at the level of structural classification.
All downstream results concerning gravitational dynamics, actions, or phenomenology
presuppose—but do not re-derive—this upstream classification.
