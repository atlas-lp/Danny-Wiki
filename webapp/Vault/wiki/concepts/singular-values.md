---
type: concept
aliases: [Singular Values]
relationships:
  - target: singular-value-decomposition
    type: is_a_component_of
  - target: isometry
    type: used_to_characterize
  - target: erhard-schmidt
    type: introduced_by
  - target: norm-of-a-linear-map
    type: determines
  - target: determinant
    type: determines_absolute_value_of
  - target: eigenvalues
    type: derived_from
tags: [linear-algebra, operator-theory, eigenvalues, linear-maps, operators, inner-product-space]
sourced_from: Linear Algebra Content
---

# Singular Values

The nonnegative square roots of the eigenvalues of T*T for an operator T, which indicate properties like injectivity and the dimension of the operator's range. The positive singular values of a linear map T are the square roots of the positive eigenvalues of the operator T*T, and are used in the singular value decomposition. For an operator T on an inner product space, the singular values are the list of nonnegative square roots of the eigenvalues of T*T. The absolute value of the determinant of T is equal to the product of its singular values.

## Relationships

- **is_a_component_of**: [[singular-value-decomposition|Singular Value Decomposition]]
- **used_to_characterize**: [[isometry|Isometry]]
- **introduced_by**: [[erhard-schmidt|Erhard Schmidt]]
- **determines**: [[norm-of-a-linear-map|Norm Of A Linear Map]]
- **determines_absolute_value_of**: [[determinant|Determinant]]
- **derived_from**: [[eigenvalues|Eigenvalues]]

---
*Extracted from: Linear Algebra Content*