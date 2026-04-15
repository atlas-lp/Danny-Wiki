---
type: entity
aliases: [GridSearchCV]
relationships:
  - target: grid-search-with-cross-validation
    type: implements
  - target: support-vector-classifier
    type: is_applied_to
  - target: grid-search
    type: implements
  - target: pipeline-class
    type: can_use
tags: [scikit-learn, tool, class, hyperparameter-tuning]
sourced_from: Introduction To Machine Learning With Python   A Guide For    Andreas C  MüLler And Sarah Guido    1 Content
---

# GridSearchCV

A scikit-learn class that performs grid search using cross-validation and automatically fits a new model on the entire training set using the best-performing parameter combination. A scikit-learn class that performs a grid search for optimal parameters using cross-validation.

## Relationships

- **implements**: [[grid-search-with-cross-validation|Grid Search With Cross Validation]]
- **is_applied_to**: [[support-vector-classifier|Support Vector Classifier]]
- **implements**: [[grid-search|Grid Search]]
- **can_use**: [[pipeline-class|Pipeline Class]]

---
*Extracted from: Introduction To Machine Learning With Python   A Guide For    Andreas C  MüLler And Sarah Guido    1 Content*