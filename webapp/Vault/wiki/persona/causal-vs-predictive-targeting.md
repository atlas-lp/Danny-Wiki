---
type: persona
aliases: [Causal vs Predictive Targeting]
relationships:
  - target: foster-provost
    type: related_to
  - target: thinking-patterns
    type: related_to
  - target: intellectual-evolution
    type: related_to
  - target: rhetorical-style-and-pedagogy
    type: related_to
  - target: foster-provost
    type: part_of
tags: [persona, data-science-and-machine-learning-for-business-decision-making]
---

# Causal vs Predictive Targeting

## The Counterintuitive Practice Provost Names

Provost identifies a CDM (causal data-driven decision-making) practice that "seems 'wrong' at first blush"—the widespread use of non-causal predictive models for targeting interventions like advertisements and retention incentives. This is his signature move of naming the invisible: billions of dollars in ad targeting rely on models that predict *who will buy*, not *who will buy because of the ad*, yet the industry mostly works anyway. The puzzle is why, and the deeper question is when it breaks.

## Causal Analytics as Double Prediction

Provost frames causal analytics not as a departure from predictive analytics but as its natural extension: "the fundamental thing you're doing in causal analytics is you're predicting both sides of the counterfactual." You predict what would happen if you take the action and what would happen if you don't, then compute the difference. This reframing—causal estimation *is* prediction, just applied twice—is characteristic of his insistence on building new concepts from already-understood foundations rather than introducing them as alien territory.

## Key Frameworks

The central paper is Fernández-Loría & Provost, "Causal Classification: Treatment Effect Estimation vs. Outcome Prediction" (JMLR 2022), which formally distinguishes when outcome prediction suffices for targeting decisions and when treatment effect estimation is required. The companion paper "Combining Observational and Experimental Data to Improve Large-Scale Decision-Making" (ICIS 2020) addresses the practical constraint that unconfounded counterfactual data is "quite costly and often impracticable" to acquire. Together they establish that large A/B test data should be treated not merely as a source of average treatment effects but as "a resource" for building heterogeneous causal models—simulating what would have happened for individuals under alternative actions because randomization permits counterfactual imputation.

## Concrete Cases

In online advertising (drawn from Provost's experience co-founding Dstillery), predictive models target users likely to convert. The hidden gap: a user predicted to buy may have bought anyway. The model optimizes reach to probable buyers, not incremental buyers. Provost uses this as a teaching hook precisely because the industry's apparent success obscures the inefficiency. In retention marketing, the same logic applies: targeting customers predicted to churn may waste incentives on those who would have stayed or who are unreachable regardless.

The LendingClub peer-to-peer lending case study provides a pedagogical parallel. Jasmin wants to "make as much money as possible," which requires going beyond out-of-sample prediction of default to estimating *investment returns*—a decision-theoretic framing where the predictive model is necessary but not sufficient.

## Connection to Broader Intellectual Project

This domain sits at the intersection of Provost's two deepest commitments: the gap between predictive models and actionable decisions, and the need for rigorous causal reasoning in data-driven practice. His career arc from cost-sensitive classification (1990s) through ad-tech targeting (2000s-2010s) to formal causal classification (2020s) traces a progressive sharpening of the same question: when does a good predictive model actually lead to a good decision? The answer increasingly requires counterfactual reasoning—connecting this work directly to his research on counterfactual explanations (with Martens on Facebook Likes, and later with Goethals on prompt-counterfactuals for generative AI). For Provost, the causal-vs-predictive distinction is not an academic nicety but the central unsolved tension in applied data science.

---
*Part of the [[foster-provost|Foster Provost]] persona knowledge base*
