---
type: entity
aliases: [Pipeline Class]
relationships:
  - target: pipeline-method
    type: implements
  - target: make-pipeline
    type: is_created_by
  - target: grid-search-cv
    type: is_used_with
tags: [scikit-learn, class]
sourced_from: Introduction To Machine Learning With Python   A Guide For    Andreas C  MüLler And Sarah Guido    1 Content
---

# Pipeline Class

A scikit-learn class that allows 'gluing' together multiple processing steps into a single estimator, which has fit, predict, and score methods and can be used in grid search.

## Relationships

- **implements**: [[pipeline-method|Pipeline Method]]
- **is_created_by**: [[make-pipeline|Make Pipeline]]
- **is_used_with**: [[grid-search-cv|Grid Search Cv]]

---
*Extracted from: Introduction To Machine Learning With Python   A Guide For    Andreas C  MüLler And Sarah Guido    1 Content*