---
type: concept
aliases: [Bagging]
relationships:
  - target: bootstrap
    type: uses
  - target: ensemble-of-models
    type: is_a_type_of
  - target: random-forests
    type: is_related_to
  - target: ensemble-methods
    type: is_a_variant_of
  - target: leo-breiman
    type: introduced_by
  - target: random-forest
    type: is_a_foundation_for
  - target: boosting
    type: compared-to
tags: [ensemble-learning, modeling, bootstrap, predictive-modeling, machine-learning, ensemble-method, resampling]
sourced_from: Practical Statistics For Data Scientists   50+ Essential    Bruce, Peter, Bruce, Andrew, Gedeck, Pet Content
---

# Bagging

A process, short for "bootstrap aggregating," where multiple models are run on bootstrap samples and their predictions are aggregated to improve performance over a single model. A principle for predictive modeling based on the 'wisdom of crowds' where averaging or taking majority votes of multiple models is used to improve accuracy. An ensemble method, short for "bootstrap aggregating," where each new model is fitted to a bootstrap resample of the training data. An ensemble machine learning method that is often contrasted with boosting.

## Relationships

- **uses**: [[bootstrap|Bootstrap]]
- **is_a_type_of**: [[ensemble-of-models|Ensemble Of Models]]
- **is_related_to**: [[random-forests|Random Forests]]
- **is_a_variant_of**: [[ensemble-methods|Ensemble Methods]]
- **introduced_by**: [[leo-breiman|Leo Breiman]]
- **is_a_foundation_for**: [[random-forest|Random Forest]]
- **compared-to**: [[boosting|Boosting]]

---
*Extracted from: Practical Statistics For Data Scientists   50+ Essential    Bruce, Peter, Bruce, Andrew, Gedeck, Pet Content*