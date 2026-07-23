# Contributing

## Purpose

This repository is maintained as a professional engineering product.

Contributions should strengthen the playbook without expanding its scope unnecessarily. Every change should be practical, evidence-informed, maintainable and consistent with the repository's architectural decisions.

---

# Branching Strategy

Use short-lived feature branches created from `main`.

Examples:

- `feature/ch12-quality-engineering`
- `feature/ch13-risk-based-engineering`
- `docs/update-roadmap`
- `adr/knowledge-sources`

Changes are merged through pull requests.

---

# Commit Messages

Use clear, imperative commit messages.

Examples:

- `docs: add quality engineering chapter`
- `docs: clarify release confidence guidance`
- `adr: define knowledge sources and evidence policy`
- `fix: correct broken chapter link`

Prefer one logical change per commit.

---

# Chapter Standard

Every major chapter should answer one practical engineering question and be independently valuable.

Required structure:

1. Engineering Question
2. Purpose
3. Primary Diagram
4. Principles or Model
5. Practical Guidance
6. Common Mistakes
7. Checklist
8. Key Takeaways
9. Related Chapters
10. References and Further Reading, when relevant
11. Revision History

A chapter should not become an encyclopedia. It should solve a real engineering problem clearly and practically.

---

# Diagram Guidance

Use Mermaid for diagrams that materially improve understanding.

Guidelines:

- Prefer one primary diagram per chapter.
- Keep diagrams conceptual and technology-independent.
- Avoid decorative diagrams.
- Ensure the surrounding text explains the model.
- Keep node labels concise and readable on GitHub.

---

# Evidence and References

Follow [ADR-0002](adr/ADR-0002-knowledge-sources-and-evidence.md).

References should improve accuracy, credibility or usefulness.

Use recognized standards, research, influential literature and practical experience appropriately. Do not add references merely for authority or appearance.

Inline citations are appropriate when a specific definition, quotation, model or externally attributable claim requires precise attribution.

---

# ADR Usage

Create an Architecture Decision Record when a decision:

- Changes repository scope or structure.
- Establishes a long-term contribution rule.
- Introduces a significant content or governance standard.
- Has meaningful alternatives or consequences.
- Would otherwise be repeatedly debated.

Do not create ADRs for routine edits or reversible formatting decisions.

---

# Pull Request Requirements

A pull request should include:

- A clear purpose.
- A concise summary of changes.
- The engineering problem addressed.
- Relevant decisions or references.
- Known limitations or follow-up work.

Keep pull requests focused. Unrelated changes should be separated.

---

# Review Quality Gates

Before merge, verify:

- [ ] The change supports the repository mission.
- [ ] The scope is clear and proportionate.
- [ ] The content solves a real engineering problem.
- [ ] Claims are accurate and appropriately grounded.
- [ ] The writing is clear, concise and technology-independent where possible.
- [ ] The primary diagram is understandable and necessary.
- [ ] Practical guidance is actionable.
- [ ] Common mistakes and trade-offs are visible.
- [ ] Links and Mermaid diagrams render correctly.
- [ ] Related chapters and revision history are updated.
- [ ] The change complies with relevant ADRs.

---

# Definition of Done

A contribution is complete when:

- The content has been self-reviewed.
- The pull request quality gates pass.
- Review feedback is resolved.
- The change is merged into `main`.
- The feature branch is deleted.

---

# Guiding Question

Before submitting a contribution, ask:

> **Would an experienced engineer use this change to make a better engineering decision?**

If the answer is no, the change should be revised, narrowed or left out.
