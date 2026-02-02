# 01 — Problem Statement

## The upstream classification problem

Modern theoretical physics possesses powerful frameworks for constructing and analysing field theories once the field content is assumed. Representation theory classifies particle states; gauge principles organise interactions; variational methods constrain admissible actions.

What these frameworks do **not** address is a logically prior question:

> **Which classical interaction fields are capable of being fundamental in principle?**

That is, before asking how a field behaves dynamically, or whether it fits observations, one may ask whether the field is *structurally capable* of standing alone as a fundamental interaction at all.

The Fundamental Fields Theorem (FFT) is concerned exclusively with this upstream classification problem.

---

## Why this question is nontrivial

In practice, physics already distinguishes—often implicitly—between theories that are treated as *exact* in certain regimes and those that are regarded as *effective* or *phenomenological*.  

For example:

- Vacuum General Relativity is treated as rigid and exact.
- Modified gravity models typically require interpolation, screening, or regime-dependent rules.
- Gauge theories rely on independently specified charge sectors.
- Effective field theories openly acknowledge cutoffs and truncation.

Despite this, gravity, gauge fields, and effective descriptions are frequently discussed on equal footing, without an explicit structural criterion explaining why their status differs.

The FFT addresses this inconsistency by making explicit the criteria already applied tacitly.

---

## What “classification” means here

The classification undertaken in the FFT is **structural**, not phenomenological.

It does **not** ask:

- which theories fit data best,
- which models are simplest,
- or which interactions quantise most cleanly.

Instead, it asks:

> If a classical interaction field is claimed to be fundamental, what minimal structural requirements must it satisfy, and which fields meet those requirements?

This is a question about **admissibility**, not empirical adequacy.

A field may be empirically successful yet fail to qualify as fundamental under the criteria adopted here. The FFT does not treat that as a criticism; it treats it as a classification result.

---

## Why this question has been avoided

There are three main reasons why this upstream classification problem has rarely been stated explicitly:

1. **The success of effective field theory**  
   Modern physics tolerates open, regulator-dependent frameworks because they work. This has blurred the distinction between effective and fundamental descriptions.

2. **The special treatment of gravity**  
   Gravity is often treated geometrically rather than as a field to be compared structurally with others, allowing its exceptional rigidity to pass without explanation.

3. **Reluctance to formalise “fundamental”**  
   The term is widely used but rarely defined, as definitions invite philosophical scrutiny.

As a result, an implicit hierarchy is relied upon in practice but has not been formalised as a theorem.

---

## The core question posed by the FFT

The FFT asks a single upstream question:

> **Can a classical interaction field regulate its own conservation laws, exhaust its degrees of freedom under symmetry, and remain internally consistent without external bookkeeping?**

Only fields that satisfy this requirement can qualify as fundamental in the sense defined in this work.

The remainder of the repository develops this question precisely, fixes definitions and axioms, and applies them eliminatively to the major classes of classical fields.
