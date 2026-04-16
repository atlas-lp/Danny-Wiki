---
type: concept
aliases: [Norm of a Linear Map]
relationships:
  - target: singular-values
    type: is_determined_by
  - target: norm-of-the-adjoint
    type: is_equal_to
tags: [linear-algebra, linear-maps, normed-spaces, operator-theory, norm]
sourced_from: Linear Algebra Content
---

# Norm of a Linear Map

The norm of a linear map T, denoted ||T||, is the maximum value of ||Tv|| for all vectors v in the domain V with ||v|| <= 1, which is equal to the largest singular value of T. The smallest non-negative number c such that the norm of a transformed vector Tv is at most c times the norm of the original vector v, which is equivalent to the maximum norm of Tv for all vectors v with norm 1.

## Relationships

- **is_determined_by**: [[singular-values|Singular Values]]
- **is_equal_to**: [[norm-of-the-adjoint|Norm Of The Adjoint]]

---
*Extracted from: Linear Algebra Content*