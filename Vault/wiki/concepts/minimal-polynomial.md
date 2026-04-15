---
type: concept
aliases: [Minimal Polynomial]
relationships:
  - target: eigenvalue
    type: has-zeros-which-are
  - target: restriction-operator
    type: is-a-multiple-of-the-minimal-polynomial-of
  - target: quotient-operator
    type: is-a-multiple-of-the-minimal-polynomial-of
  - target: diagonalizable-operator
    type: determines_property_of
  - target: generalized-eigenspace-decomposition
    type: related-to
tags: [polynomial-theory, operator-theory, linear-algebra, polynomials, operators]
sourced_from: Linear Algebra Content
---

# Minimal Polynomial

An important algebraic tool used in the book to provide cleaner proofs and to characterize diagonalizable operators. For an operator T on a finite-dimensional space, it is the unique monic polynomial of smallest positive degree that results in the zero operator when T is substituted for the variable. A polynomial associated with an operator T such that p(T)=0, and any other polynomial q with q(T)=0 is a multiple of p. Its zeros are the operator's eigenvalues, and its constant term determines if the operator is invertible. A polynomial p associated with an operator T, where the condition that p and its derivative p' have no common zeros is equivalent to T being diagonalizable. A polynomial associated with an operator T, used in a condition to determine if a vector space can be decomposed into a direct sum of generalized eigenspaces.

## Relationships

- **has-zeros-which-are**: [[eigenvalue|Eigenvalue]]
- **is-a-multiple-of-the-minimal-polynomial-of**: [[restriction-operator|Restriction Operator]]
- **is-a-multiple-of-the-minimal-polynomial-of**: [[quotient-operator|Quotient Operator]]
- **determines_property_of**: [[diagonalizable-operator|Diagonalizable Operator]]
- **related-to**: [[generalized-eigenspace-decomposition|Generalized Eigenspace Decomposition]]

---
*Extracted from: Linear Algebra Content*