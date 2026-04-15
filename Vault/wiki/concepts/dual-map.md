---
type: concept
aliases: [Dual Map]
relationships:
  - target: linear-map
    type: is-a
  - target: linear-map
    type: is-derived-from
  - target: dual-space
    type: maps-from
  - target: dual-space
    type: maps-to
  - target: linear-map
    type: is_a_type_of
  - target: dual-space
    type: maps_between
  - target: annihilator
    type: related_via_null_space_to
tags: [duality, linear-maps, linear-algebra]
sourced_from: Linear Algebra Content
---

# Dual Map

For a linear map T in L(V, W), its dual map T' is a linear map in L(W', V') defined by the composition T'(φ) = φ ∘ T. For a linear map T from vector space V to W, the dual map T' is a linear map from the dual space W' to the dual space V'. Key properties shown are that T is surjective iff T' is injective, T is injective iff T' is surjective, and the matrix of T' is the transpose of the matrix of T.

## Relationships

- **is-a**: [[linear-map|Linear Map]]
- **is-derived-from**: [[linear-map|Linear Map]]
- **maps-from**: [[dual-space|Dual Space]]
- **maps-to**: [[dual-space|Dual Space]]
- **is_a_type_of**: [[linear-map|Linear Map]]
- **maps_between**: [[dual-space|Dual Space]]
- **related_via_null_space_to**: [[annihilator|Annihilator]]

---
*Extracted from: Linear Algebra Content*