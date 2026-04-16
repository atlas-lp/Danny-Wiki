---
type: concept
aliases: [Diagonalizable Operator]
relationships:
  - target: eigenvector
    type: requires-basis-of
  - target: eigenspace
    type: is-equivalent-to-direct-sum-of
  - target: minimal-polynomial
    type: is_characterized_by
  - target: simultaneous-diagonalizability
    type: is_a_precondition_for
tags: [linear-algebra, operators, diagonalization]
sourced_from: Linear Algebra Content
---

# Diagonalizable Operator

An operator on a finite-dimensional vector space is diagonalizable if it has a diagonal matrix with respect to some basis, which is equivalent to the vector space having a basis of its eigenvectors or being the direct sum of its eigenspaces. An operator T is diagonalizable if and only if its minimal polynomial p has no common zeros with its derivative p'. Two diagonalizable operators can have diagonal matrices with respect to the same basis if and only if they commute.

## Relationships

- **requires-basis-of**: [[eigenvector|Eigenvector]]
- **is-equivalent-to-direct-sum-of**: [[eigenspace|Eigenspace]]
- **is_characterized_by**: [[minimal-polynomial|Minimal Polynomial]]
- **is_a_precondition_for**: [[simultaneous-diagonalizability|Simultaneous Diagonalizability]]

---
*Extracted from: Linear Algebra Content*