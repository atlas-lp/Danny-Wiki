---
type: concept
aliases: [Pseudoinverse]
relationships:
  - target: moore-penrose-inverse
    type: is_also_known_as
  - target: singular-value-decomposition
    type: is_derived_from
tags: [linear-algebra, linear-maps, minimization-problems, inverse]
sourced_from: Linear Algebra Content
---

# Pseudoinverse

A linear map, denoted T-dagger, that provides a best approximate solution to the equation Tx = b when T is not invertible by finding the vector x with the smallest norm that minimizes ||Tx – b||. The pseudoinverse T† of a linear map T can be obtained from its singular value decomposition by interchanging the roles of the basis vectors and replacing each positive singular value s_k with 1/s_k; it equals the inverse T⁻¹ if T is invertible.

## Relationships

- **is_also_known_as**: [[moore-penrose-inverse|Moore Penrose Inverse]]
- **is_derived_from**: [[singular-value-decomposition|Singular Value Decomposition]]

---
*Extracted from: Linear Algebra Content*