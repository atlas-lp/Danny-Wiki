---
type: concept
aliases: [A/B Testing]
relationships:
  - target: experimentation
    type: is_a
  - target: causal-inference
    type: is_a
  - target: spotify
    type: used_by
  - target: bandit-modeling
    type: contrasted_with
  - target: selection-bias
    type: avoids
  - target: causal-impact-models
    type: is-a-data-source-for
tags: [experimentation, data-science, statistics, model-evaluation]
sourced_from: Foster Provost  Nyu Stern  Knowledge Base
---

# A/B Testing

A form of experimentation that provides unconfounded data by randomly assigning users to different conditions, used to test the real-world impact of new systems like machine learning algorithms. A randomized test whose data can be used to simulate and evaluate a model's performance without selection bias by only using data points where the test action matched the model's proposed action.

## Relationships

- **is_a**: [[experimentation|Experimentation]]
- **is_a**: [[causal-inference|Causal Inference]]
- **used_by**: [[spotify|Spotify]]
- **contrasted_with**: [[bandit-modeling|Bandit Modeling]]
- **avoids**: [[selection-bias|Selection Bias]]
- **is-a-data-source-for**: [[causal-impact-models|Causal Impact Models]]

---
*Extracted from: Foster Provost  Nyu Stern  Knowledge Base*