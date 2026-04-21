---
type: synthesized
aliases: ["Road Map to Data Science", "Learning Path for Data Science", "Data Science Learning Progression"]
tags: ["data-science", "learning-path", "roadmap", "machine-learning", "python"]
relationships:
  - target: data-science-for-business
    type: extends
  - target: data-analytic-thinking
    type: extends
  - target: expected-value-framework
    type: extends
---

# Data Science Roadmap

# Data Science Roadmap

A five-phase learning progression that integrates the Provost/Fawcett business-thinking framework (*Data Science for Business*) with Grus's first-principles-in-Python approach (*Data Science from Scratch*) and the CRISP-DM process model. The goal is not merely technical proficiency but the ability to deliver business impact through data.

## Phase 1: Foundations — Mathematics, Statistics, and Python

Before touching data, build comfort with the mathematical and statistical core of data science. This is non-negotiable: surface familiarity is insufficient.

- **Linear algebra**: vectors, matrices, dot products — the substrate of nearly every ML algorithm
- **Statistics**: descriptive statistics, distributions, correlation, hypothesis testing, p-values
- **Probability**: conditional probability, Bayes' theorem, expected value
- **Python fundamentals**: syntax, data structures (lists, dicts, sets), functions, comprehensions

*Primary resource*: Build implementations yourself (Grus's philosophy — hacking on things is how hacking skills are learned). Use toy datasets deliberately; clarity matters more than scale at this stage.

## Phase 2: Data-Analytic Thinking and Problem Framing

Technical skill without business framing produces models that don't matter. Before modeling, learn to decompose a business problem into a data science task.

- **Data-analytic thinking**: reframe every business question as a data question — what is the target variable, what constitutes a case, what would a useful prediction look like?
- **CRISP-DM**: Business Understanding → Data Understanding → Data Preparation → Modeling → Evaluation → Deployment. Treat this as a cognitive checklist, not a waterfall.
- **Problem taxonomy**: classification vs. regression vs. clustering vs. similarity matching vs. causal inference — know which tool fits which problem type before building anything
- **Beware temporal leakage**: when a feature is suspiciously correlated with the target, it may encode post-outcome information. Always ask: would this variable be available at prediction time?

*Primary resource*: *Data Science for Business* (Provost & Fawcett), especially the LendingClub case study as a worked example of problem decomposition.

## Phase 3: Core Algorithms from Scratch, Then in Libraries

Build each algorithm from scratch first; then switch to the production library. Understanding the internals prevents misuse.

**Supervised learning**
- Linear and logistic regression (gradient descent by hand)
- Decision trees (information gain, splitting criteria)
- k-Nearest Neighbors
- Naive Bayes (especially for NLP)

**Unsupervised learning**
- k-Means clustering
- Hierarchical clustering
- Dimensionality reduction (PCA concepts)

**Feature engineering**
- Encoding categoricals, handling missing data, scaling
- Feature selection vs. feature extraction
- Domain-driven feature construction

*Transition*: Once you have built each algorithm manually, move to scikit-learn, pandas, and NumPy for practical work. The from-scratch implementations are for understanding; the libraries are for productivity.

## Phase 4: Evaluation, Expected Value, and Business Connection

A model is not finished when it achieves good accuracy on a test set. Evaluation must be yoked to the decision context.

- **ROC curves and AUC**: understand what they measure and when accuracy is the wrong metric
- **Cost-sensitive evaluation**: different errors have different costs; weight them accordingly
- **The expected value framework**: connect probabilistic model outputs to optimal decisions by computing the expected payoff of each possible action under uncertainty. This is the bridge from prediction to decision.
  - Use expected value to: (1) choose between algorithms, (2) determine whether ML is even needed, (3) calculate expected ROI for a proposed DS initiative
  - Formula: split evaluation into *R* (return if successful), *I* (investment), and *p(S)* (probability of success)
- **Calibration**: predicted probabilities must be calibrated to use expected value correctly; a model that says "70% probability" should be right 70% of the time

*Key principle*: Predictive analytics produces probabilities, not fixed values. Expected value is the correct framework for acting under that uncertainty.

## Phase 5: Business Impact, Deployment, and Advanced Topics

The final phase moves from building models to delivering value at scale and understanding the limits of purely predictive framing.

- **Deployment and MLOps basics**: how models go from notebooks to production systems; monitoring for drift
- **Causal vs. predictive thinking**: high-scoring individuals from a predictive model are not necessarily the right targets for an intervention. If you are targeting ads, sending retention offers, or making treatment decisions, you need causal reasoning (uplift modeling, A/B tests) not just outcome prediction.
- **Explainability**: for decisions that affect individuals, understand why a model produced a specific output — not just global feature importance but instance-level explanation
- **Scale and ethics**: big data changes the scale of activities without changing their kind; existing legal and ethical frameworks may not be adequate. Understand civil rights implications of automated decision-making.
- **Network analysis** (optional but high-value): graph-based features often capture information that tabular features miss
- **NLP basics**: tokenization, bag-of-words, TF-IDF, embeddings — text is one of the richest data sources in business

## Summary Table

| Phase | Focus | Key Tools/Concepts |
|---|---|---|
| 1 | Math, stats, Python | Linear algebra, probability, Python fundamentals |
| 2 | Problem framing | Data-analytic thinking, CRISP-DM, problem taxonomy |
| 3 | Algorithms | Regression, trees, clustering, feature engineering |
| 4 | Evaluation | ROC, expected value framework, cost-sensitive metrics |
| 5 | Impact & limits | Deployment, causal reasoning, explainability, ethics |

## Guiding Principles

1. **Always connect to a decision**: a model that does not change an action is not delivering value. Use the expected value framework to make the connection explicit.
2. **Build before you import**: understanding internals prevents misuse of libraries.
3. **Frame before you model**: CRISP-DM business understanding is not bureaucratic overhead — it prevents building the right answer to the wrong question.
4. **Predictive ≠ causal**: if the goal is to intervene, not just predict, the modeling approach must change.
5. **Explanation is not optional when stakes are high**: instance-level counterfactual reasoning matters for trust, privacy, and contestability.