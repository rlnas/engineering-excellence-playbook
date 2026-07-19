# ADR-0001 — Repository Scope and Product Direction

**Status:** Accepted

**Date:** 2026-07-19

---

# Context

Engineering knowledge repositories often become difficult to maintain because they continuously expand in scope.

They evolve into collections of notes, tutorials, tool comparisons and unrelated documents rather than a coherent engineering reference.

To remain valuable over time, the Engineering Excellence Playbook requires clear boundaries.

---

# Decision

The Engineering Excellence Playbook is a product.

It is **not**:

- an encyclopedia
- a technology wiki
- a personal notebook
- a certification guide
- a collection of tutorials

It is a curated engineering reference focused on solving real engineering problems.

Every contribution must support that objective.

---

# Acceptance Criteria

A contribution is accepted only if it:

- Solves a real engineering problem.
- Is based on engineering principles rather than vendor-specific tooling.
- Can be applied in professional engineering environments.
- Remains useful over time.
- Fits the published roadmap.

---

# Rejection Criteria

The following content should not be added:

- Technology tutorials.
- Product comparisons.
- Personal study notes.
- Experimental ideas without practical value.
- Vendor documentation.
- Marketing material.

These belong elsewhere or remain in the Parking Lot until they justify inclusion.

---

# Guiding Question

Before creating a new chapter, ask:

> **"Would an experienced engineer use this to make a better engineering decision?"**

If the answer is **no**, the content does not belong in this repository.

---

# Consequences

This decision intentionally limits the repository's scope.

The result should be a smaller, higher-quality playbook that engineers can trust and return to over time.

Quality takes priority over completeness.