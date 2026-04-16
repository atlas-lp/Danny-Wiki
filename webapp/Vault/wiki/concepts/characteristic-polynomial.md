---
type: concept
aliases: [Characteristic Polynomial]
relationships:
  - target: eigenvalue
    type: has-zeros
  - target: cayley-hamilton-theorem
    type: is-used-in
  - target: trace-of-an-operator
    type: is_related_to
  - target: determinant
    type: defined_using
  - target: eigenvalues
    type: has_as_zeros
  - target: trace
    type: related_to
tags: [linear-algebra, polynomials, operator-theory, operators]
sourced_from: Linear Algebra Content
---

# Characteristic Polynomial

A polynomial associated with an operator T on a complex vector space, whose degree is the dimension of the space and whose zeros are the eigenvalues of T. For an operator T on an n-dimensional complex vector space with eigenvalues λ₁, ..., λₙ, its characteristic polynomial is (z - λ₁)⋯(z - λₙ). The trace of T is equal to the negative of the coefficient of the zⁿ⁻¹ term in this polynomial. A polynomial associated with an operator T, defined by the mapping z to det(zI - T). Its zeros are the eigenvalues of T, and its coefficients are related to the trace and determinant of T.

## Relationships

- **has-zeros**: [[eigenvalue|Eigenvalue]]
- **is-used-in**: [[cayley-hamilton-theorem|Cayley Hamilton Theorem]]
- **is_related_to**: [[trace-of-an-operator|Trace Of An Operator]]
- **defined_using**: [[determinant|Determinant]]
- **has_as_zeros**: [[eigenvalues|Eigenvalues]]
- **related_to**: [[trace|Trace]]

---
*Extracted from: Linear Algebra Content*