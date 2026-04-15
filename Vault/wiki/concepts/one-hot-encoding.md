---
type: concept
aliases: [One-Hot Encoding]
relationships:
  - target: feature-engineering
    type: is_a
  - target: neural-network-input-preparation
    type: is_a_method_of
  - target: dummy-variables
    type: is-a-method-for-creating
  - target: categorical-features
    type: encodes
  - target: dummy-encoding
    type: is_similar_to
  - target: get-dummies
    type: is_implemented_by
  - target: onehotencoder
    type: is_implemented_by
  - target: preprocessing
    type: is_a_type_of
tags: [feature-engineering, data-preprocessing, encoding, data-representation]
sourced_from: Introduction To Machine Learning With Python   A Guide For    Andreas C  MüLler And Sarah Guido    1 Content
---

# One-Hot Encoding

A method for representing categorical variables where a single feature is encoded using multiple new binary features, with exactly one of the new features being 1 for each data point. A technique for representing categorical data, also known as one-out-of-N encoding, where each category is converted into a binary vector.

## Relationships

- **encodes**: [[categorical-features|Categorical Features]]
- **is_similar_to**: [[dummy-encoding|Dummy Encoding]]
- **is_implemented_by**: [[get-dummies|Get Dummies]]
- **is_implemented_by**: [[onehotencoder|Onehotencoder]]
- **is_a_type_of**: [[preprocessing|Preprocessing]]

---
*Extracted from: Introduction To Machine Learning With Python   A Guide For    Andreas C  MüLler And Sarah Guido    1 Content*

---
*Also referenced in: Practical Statistics For Data Scientists   50+ Essential    Bruce, Peter, Bruce, Andrew, Gedeck, Pet Content*

---
*Also referenced in: ǂThe ǂHundred Page Machine Learning Book    Andriy Burkov    Lugar De PublicacióN No Identificado, 2 Content*