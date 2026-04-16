---
type: concept
aliases: [Multiple Regression]
relationships:
  - target: root-mean-squared-error
    type: evaluated_by
  - target: residual-standard-error
    type: evaluated_by
  - target: adjusted-r-squared
    type: evaluated_by
  - target: t-statistic
    type: evaluated_by
  - target: model-selection
    type: uses
  - target: linear-independence
    type: requires
  - target: gradient-descent
    type: is-fit-using
  - target: regularization
    type: uses
tags: [modeling, machine-learning, statistics, regression]
sourced_from: Data Science From Scratch   First Principles With Python    Joel Grus, (Software Engineer)    O Reil Content
---

# Multiple Regression

A statistical model that uses several independent variables to predict the outcome of a single dependent variable. A statistical model whose coverage includes its underlying assumptions, model fitting, goodness of fit, and regularization.

## Relationships

- **requires**: [[linear-independence|Linear Independence]]
- **is-fit-using**: [[gradient-descent|Gradient Descent]]
- **uses**: [[regularization|Regularization]]

---
*Extracted from: Data Science From Scratch   First Principles With Python    Joel Grus, (Software Engineer)    O Reil Content*

---
*Also referenced in: Practical Statistics For Data Scientists   50+ Essential    Bruce, Peter, Bruce, Andrew, Gedeck, Pet Content*