# ADR-0001 — Standards Edition

- **Status:** Accepted
- **Date:** 25 July 2026
- **Version:** 2.0.0
- **Authors:** Project ButterFly

---

# Title

Establish the Standards Edition as the Third Foundational Layer of Project ButterFly

---

# Context

Project ButterFly began by defining its permanent principles through the Constitution and expanding those principles into domain-specific philosophies through the Charters.

While these documents established *why* thoughtful software should be built, they did not define *how* engineering teams should consistently apply those principles during day-to-day development.

As the project evolved, a need emerged for a structured collection of engineering practices that could transform philosophy into repeatable actions while remaining independent of specific technologies and frameworks.

Without this layer, teams would share the same philosophy but could implement it inconsistently.

---

# Problem Statement

How should Project ButterFly translate its philosophy into practical, repeatable engineering practices without compromising the timeless nature of the Constitution or the philosophical intent of the Charters?

---

# Alternatives Considered

## Option 1 — Expand the Charters

Continue adding implementation guidance directly into the existing Charters.

### Advantages

- Fewer documents.
- Simple repository structure.

### Disadvantages

- Blurs the distinction between philosophy and practice.
- Makes Charters increasingly implementation-focused.
- Reduces long-term maintainability.

---

## Option 2 — Create Standards

Introduce a dedicated Standards layer responsible for defining repeatable engineering practices.

### Advantages

- Clear separation of responsibilities.
- Philosophy remains timeless.
- Engineering practices can evolve independently.
- Improves consistency across projects.
- Scales naturally as the methodology grows.

### Disadvantages

- Introduces an additional documentation layer.
- Requires governance to maintain consistency.

---

# Decision

Project ButterFly will introduce **Standards** as the third foundational layer of the methodology.

The Standards Edition defines consistent engineering practices while preserving the timeless nature of the Constitution and the philosophical focus of the Charters.

The methodology is therefore organized as follows:

```text
Constitution
        ↓
Charters
        ↓
Standards
        ↓
Guides
        ↓
Reference Implementations
```

Each layer serves a distinct purpose and builds upon the one before it.

---

# Consequences

## Positive

- Clear separation between principles, philosophy, and practices.
- Repeatable engineering guidance.
- Improved consistency across projects.
- Better onboarding for new contributors.
- Strong foundation for future Guides and Reference Implementations.

## Trade-offs

- Additional documentation to maintain.
- Contributors must understand the distinction between Charters, Standards, and Guides.

---

# Standards Edition Scope

Version 2.0 establishes ten engineering standards grouped into three areas.

## Communication

- Standards Guide
- Naming Standard
- Documentation Standard

## Organization

- Repository Structure Standard
- Code Style Standard

## Quality & Validation

- Testing Standard
- Code Review Standard
- Release Standard
- Versioning Standard
- Decision Record Standard

---

# Rationale

Separating philosophy from engineering practice allows each layer of the methodology to evolve at an appropriate pace.

- The Constitution remains stable.
- Charters mature slowly as engineering philosophy evolves.
- Standards adapt as engineering practices improve.
- Guides evolve continuously through practical experience.

This separation preserves clarity while supporting long-term growth.

---

# Implementation

Version 2.0 introduces:

- Standards folder
- Standards README
- Ten engineering standards
- Updated repository documentation
- Reading order across methodology layers

Future editions will build upon these standards through practical implementation guides and reference projects.

---

# Review

This decision should be reviewed only if the structure of Project ButterFly changes significantly.

Routine additions of new standards do not require revisiting this ADR.

---

# References

Related Documents:

- Constitution
- Charters
- Standards
- Release Standard
- Decision Record Standard

---

# Closing Statement

The Constitution defines what should never change.

The Charters explain what we believe.

The Standards establish how we work.

Together, they transform engineering philosophy into repeatable practice.

---

> **Build with Purpose.**
>
> **Design with Empathy.**
>
> **Engineer with Excellence.**
>
> **Preserve the Why.**
>
> — Project ButterFly 🦋