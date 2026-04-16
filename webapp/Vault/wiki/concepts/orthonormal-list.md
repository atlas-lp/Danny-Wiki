---
type: concept
aliases: [Orthonormal List]
relationships:
  - target: norm
    type: requires
  - target: orthogonality
    type: requires
  - target: orthonormal-basis
    type: is_a_precondition_for
  - target: gram-schmidt-procedure
    type: is_produced_by
  - target: unitary-matrix
    type: forms_columns_of
tags: [vector-space, basis, linear-algebra, vectors, orthogonality]
sourced_from: Linear Algebra Content
---

# Orthonormal List

A list of vectors in an inner product space where each vector has a norm of 1 and is orthogonal to all other vectors in the list; every orthonormal list is linearly independent. A list of vectors in an inner product space where each vector has a norm of 1 and is orthogonal to every other vector in the list. A list of vectors produced by the Gram-Schmidt procedure, which can form the columns of a unitary matrix or be used in the Singular Value Decomposition.

## Relationships

- **requires**: [[norm|Norm]]
- **requires**: [[orthogonality|Orthogonality]]
- **is_a_precondition_for**: [[orthonormal-basis|Orthonormal Basis]]
- **is_produced_by**: [[gram-schmidt-procedure|Gram Schmidt Procedure]]
- **forms_columns_of**: [[unitary-matrix|Unitary Matrix]]

---
*Extracted from: Linear Algebra Content*