---
type: concept
aliases: [Grid Search]
relationships:
  - target: hyperparameter-tuning
    type: is_a_type_of
  - target: support-vector-classifier
    type: is_applied_to
  - target: gridsearchcv
    type: implemented_by
  - target: nested-cross-validation
    type: used_in
  - target: grid-search-cv
    type: implemented_by
  - target: pipeline-method
    type: can_use
  - target: cross-validation
    type: uses
  - target: pipeline-scikit-learn
    type: uses
tags: [hyperparameter-tuning, model-selection]
sourced_from: Introduction To Machine Learning With Python   A Guide For    Andreas C  MüLler And Sarah Guido    1 Content
---

# Grid Search

A method for parameter tuning that exhaustively searches through a specified grid of parameter values by training and evaluating a model for each combination. A method for hyperparameter tuning that involves exhaustively searching through a specified grid of parameter values to find the optimal combination for a model. A model selection technique used to find the optimal parameters for a model by exhaustively searching through a manually specified grid of hyperparameter values. A powerful strategy for parameter selection that searches over preprocessing and model parameters by trying all possible combinations of the specified values. A technique for tuning model parameters by searching over a specified grid of parameter values, often used in conjunction with cross-validation.

## Relationships

- **is_applied_to**: [[support-vector-classifier|Support Vector Classifier]]
- **implemented_by**: [[gridsearchcv|Gridsearchcv]]
- **used_in**: [[nested-cross-validation|Nested Cross Validation]]
- **implemented_by**: [[grid-search-cv|Grid Search Cv]]
- **can_use**: [[pipeline-method|Pipeline Method]]
- **uses**: [[cross-validation|Cross Validation]]
- **uses**: [[pipeline-scikit-learn|Pipeline Scikit Learn]]

---
*Extracted from: Introduction To Machine Learning With Python   A Guide For    Andreas C  MüLler And Sarah Guido    1 Content*

---
*Also referenced in: ǂThe ǂHundred Page Machine Learning Book    Andriy Burkov    Lugar De PublicacióN No Identificado, 2 Content*