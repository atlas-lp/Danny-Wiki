---
type: concept
aliases: [Curse of Dimensionality]
relationships:
  - target: nearest-neighbors-classification
    type: affects
  - target: dimensionality-reduction
    type: mitigated_by
tags: [machine-learning-theory, dimensionality, machine-learning, data-science]
sourced_from: Data Science From Scratch   First Principles With Python    Joel Grus, (Software Engineer)    O Reil Content
---

# Curse of Dimensionality

The phenomenon where high-dimensional spaces are so vast that points tend not to be close to one another, causing problems for algorithms like k-nearest neighbors. A phenomenon where as the number of dimensions increases, the average distance between points increases and the ratio of the closest distance to the average distance approaches 1, making points seem equally far apart.

## Relationships

- **affects**: [[nearest-neighbors-classification|Nearest Neighbors Classification]]
- **mitigated_by**: [[dimensionality-reduction|Dimensionality Reduction]]

---
*Extracted from: Data Science From Scratch   First Principles With Python    Joel Grus, (Software Engineer)    O Reil Content*