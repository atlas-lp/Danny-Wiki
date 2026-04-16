---
type: entity
aliases: [scikit-learn]
relationships:
  - target: linear-regression
    type: implements
  - target: logistic-regression
    type: implements
  - target: support-vector-machine
    type: implements
  - target: cross-validation
    type: implements
  - target: logistic-regression-cv
    type: contains
  - target: fitted-values
    type: is_used_to_calculate
  - target: naive-bayes
    type: implements
  - target: k-nearest-neighbors
    type: implements
  - target: sklearn-decisiontreeclassifier
    type: contains
  - target: gridsearchcv
    type: contains
  - target: python
    type: library_of
  - target: numpy
    type: depends-on
  - target: scipy
    type: depends-on
  - target: ridge-regression
    type: provides_implementation_of
  - target: lasso-regression
    type: provides_implementation_of
  - target: elastic-net
    type: provides_implementation_of
  - target: min-max-scaler
    type: provides
  - target: standard-scaler
    type: provides
  - target: normalizer
    type: provides
  - target: fit-transform-method
    type: provides
  - target: k-means-clustering
    type: implements
  - target: agglomerative-clustering
    type: implements
  - target: ward-linkage
    type: implements
  - target: onehotencoder
    type: contains
  - target: python
    type: is_a_library_for
  - target: libsvm
    type: uses
  - target: machine-learning
    type: is_library_for
tags: [python-library, machine-learning, software]
sourced_from: Data Science From Scratch   First Principles With Python    Joel Grus, (Software Engineer)    O Reil Content
---

# scikit-learn

A Python module providing implementations for various models including Linear Regression, Ridge regression, Lasso regression, Logistic Regression, and Support Vector Machines. A machine learning library that does the 'heavy lifting' and uses really good optimization algorithms, preventing the need to write them by hand.

## Relationships

- **uses**: [[libsvm|Libsvm]]
- **is_library_for**: [[machine-learning|Machine Learning]]

---
*Extracted from: Data Science From Scratch   First Principles With Python    Joel Grus, (Software Engineer)    O Reil Content*

---
*Also referenced in: Introduction To Machine Learning With Python   A Guide For    Andreas C  MüLler And Sarah Guido    1 Content*

---
*Also referenced in: Practical Statistics For Data Scientists   50+ Essential    Bruce, Peter, Bruce, Andrew, Gedeck, Pet Content*

---
*Also referenced in: Python For Data Analysis  Data Wrangling With Pandas, Numpy,    Wes Mckinney    2Nd, 2017    O Reill Content*

---
*Also referenced in: ǂThe ǂHundred Page Machine Learning Book    Andriy Burkov    Lugar De PublicacióN No Identificado, 2 Content*