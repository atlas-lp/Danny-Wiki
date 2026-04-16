---
type: entity
aliases: [GridSearchCV]
relationships:
  - target: grid-search
    type: implements
  - target: nested-cross-validation
    type: can_be_used_in
  - target: scikit-learn
    type: is_a_component_of
tags: [scikit-learn, hyperparameter-tuning, model-selection, tool]
sourced_from: Introduction To Machine Learning With Python   A Guide For    Andreas C  MüLler And Sarah Guido    1 Content
---

# GridSearchCV

A scikit-learn class that performs an exhaustive grid search over a specified parameter grid for an estimator, using cross-validation to evaluate each combination. A scikit-learn class that performs an exhaustive search over a specified parameter grid to find the best model parameters using cross-validation.

## Relationships

- **implements**: [[grid-search|Grid Search]]
- **can_be_used_in**: [[nested-cross-validation|Nested Cross Validation]]
- **is_a_component_of**: [[scikit-learn|Scikit Learn]]

---
*Extracted from: Introduction To Machine Learning With Python   A Guide For    Andreas C  MüLler And Sarah Guido    1 Content*

---
*Also referenced in: Practical Statistics For Data Scientists   50+ Essential    Bruce, Peter, Bruce, Andrew, Gedeck, Pet Content*