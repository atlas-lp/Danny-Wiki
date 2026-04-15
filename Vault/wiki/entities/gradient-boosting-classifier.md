---
type: entity
aliases: [GradientBoostingClassifier]
relationships:
  - target: gradient-boosted-decision-trees
    type: is-an-implementation-of
  - target: decision-function
    type: implements
  - target: predict-proba
    type: implements
  - target: scikit-learn
    type: is_part_of
tags: [scikit-learn, model-implementation, machine-learning-model, classifier]
sourced_from: Introduction To Machine Learning With Python   A Guide For    Andreas C  MüLler And Sarah Guido    1 Content
---

# GradientBoostingClassifier

An implementation of the gradient boosting algorithm that, by default, uses 100 trees of maximum depth 3 and a learning rate of 0.1. A specific classifier model in scikit-learn that can provide uncertainty estimates through both `decision_function` and `predict_proba` methods.

## Relationships

- **is-an-implementation-of**: [[gradient-boosted-decision-trees|Gradient Boosted Decision Trees]]
- **implements**: [[decision-function|Decision Function]]
- **implements**: [[predict-proba|Predict Proba]]
- **is_part_of**: [[scikit-learn|Scikit Learn]]

---
*Extracted from: Introduction To Machine Learning With Python   A Guide For    Andreas C  MüLler And Sarah Guido    1 Content*