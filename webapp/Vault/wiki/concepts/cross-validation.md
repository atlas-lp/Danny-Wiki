---
type: concept
aliases: [Cross-Validation]
relationships:
  - target: hyperparameter-tuning
    type: is_used_for
  - target: scikit-learn
    type: implemented_in
  - target: model-selection
    type: validates
  - target: hyperparameters
    type: is_used_to_tune
  - target: boosting
    type: is_important_for
  - target: principal-components-analysis-pca
    type: used-for
  - target: hyperparameters
    type: used-for
  - target: model-evaluation
    type: is_a_method_for
  - target: parameter-tuning
    type: is_a_method_for
  - target: train-test-split
    type: is_an_improvement_on
  - target: grid-search
    type: is_used_by
  - target: information-leakage
    type: is_vulnerable_to
  - target: logisticregression
    type: is-used-to-evaluate
tags: [model-evaluation, parameter-tuning, resampling-method, resampling, hyperparameter-tuning, statistics]
sourced_from: Introduction To Machine Learning With Python   A Guide For    Andreas C  MüLler And Sarah Guido    1 Content
---

# Cross-Validation

An advanced method in machine learning that receives particular focus for its use in model evaluation and parameter tuning. A model evaluation technique that provides a more robust measure of generalization performance than a single train-test split by creating multiple splits of the data and aggregating the results. A model evaluation technique where a dataset is split into training and validation folds to assess how a model will generalize to an independent dataset. A method for obtaining a quantitative measure of a classifier's performance and for tuning model hyperparameters, such as the regularization parameter C in Logistic Regression. A procedure for evaluating how well a model will generalize to new data by splitting the data into folds and repeatedly training and testing on different subsets.

## Relationships

- **is_a_method_for**: [[model-evaluation|Model Evaluation]]
- **is_a_method_for**: [[parameter-tuning|Parameter Tuning]]
- **is_an_improvement_on**: [[train-test-split|Train Test Split]]
- **is_used_by**: [[grid-search|Grid Search]]
- **is_vulnerable_to**: [[information-leakage|Information Leakage]]
- **is-used-to-evaluate**: [[logisticregression|Logisticregression]]

---
*Extracted from: Introduction To Machine Learning With Python   A Guide For    Andreas C  MüLler And Sarah Guido    1 Content*

---
*Also referenced in: Practical Statistics For Data Scientists   50+ Essential    Bruce, Peter, Bruce, Andrew, Gedeck, Pet Content*

---
*Also referenced in: Python For Data Analysis  Data Wrangling With Pandas, Numpy,    Wes Mckinney    2Nd, 2017    O Reill Content*

---
*Also referenced in: ǂThe ǂHundred Page Machine Learning Book    Andriy Burkov    Lugar De PublicacióN No Identificado, 2 Content*