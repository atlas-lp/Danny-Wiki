---
type: persona
aliases: [Counterfactual Explanations for Inference]
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

# Counterfactual Explanations for Inference

## Distinctive Take

Provost's core position is that explanations for data-driven inferences should operate at the **instance level**, not the model level, and should be framed as **evidence counterfactuals**: "if you hadn't had this specific evidence… then you wouldn't have gotten this ad" or this classification. This is non-obvious because the dominant paradigm in explainable AI focuses on explaining *how a model works globally* (feature importances, decision boundaries), whereas Provost insists that what matters—particularly for privacy, transparency, and user control—is explaining *why this specific inference was drawn about this specific person*. He explicitly distinguishes "model level" from "domain level" explanations (drawing on Robnik-Šikonja and Kononenko), arguing that conflating the two "can lead to confusion." The explanation is not "the model weights sexual orientation-related Likes heavily" but rather "these particular Likes you performed are the evidence that caused the model to classify you as gay."

## Key Framework: The Evidence Counterfactual

The evidence counterfactual identifies the minimal set of input features (e.g., Facebook Likes) whose removal would change the inference. Provost treats the predictive model as an **evidence-combining system**—it ingests fine-grained behavioral data and crosses a probability threshold to trigger a classification or action. The counterfactual explanation identifies which specific pieces of evidence pushed the score past that threshold. For a more detailed counterfactual, one can "move the threshold down" to surface additional contributing evidence. This framework was developed primarily with David Martens and extended in 2026 with Sofie Goethals and João Sedoc to **prompt-counterfactual explanations** for generative AI systems, where the "evidence" becomes components of a prompt rather than behavioral features.

## Concrete Cases

The signature example is **Facebook Likes and sexual orientation inference**. For a user named "Manu," the system shows which specific Likes (e.g., watching *The Big Bang Theory*, listening to Coldplay, liking particular phrases) caused a high predicted probability of being gay. Figure 1 from the paper demonstrates dramatic per-user variation: removing fewer than 15 Likes for one user causes a steep drop in predicted probability, while the same number of removals barely affects another user. Provost uses this to anchor the quantitative argument that "usually users must cloak only a small portion of their actions to inhibit inference." A second example involves **corporate residence fraud detection**, where the counterfactual identifies specific evidence like membership in "Fairway Golf Club"—an entity frequently associated with fraud—as the pivotal factor crossing the classification threshold.

## The Cloaking Device: From Transparency to Control

Provost bridges explanation to **actionable privacy control** through the "cloaking device," which allows users to inhibit specific pieces of evidence from future inferences without withdrawing from the platform entirely. The design reflects his broader conviction that transparency without agency is insufficient: "I would like to know what are the inferences that Facebook is drawing about me and what is the basis for those inferences," followed by the ability to cloak selectively. This connects directly to his civil rights work with Barocas and Honavar on data science and civil rights, where inference-based harms (incorrect or unwanted classifications) are framed as a societal concern distinct from traditional data confidentiality.

## Connection to Broader Intellectual Project

Counterfactual explanations sit at the intersection of Provost's two deepest commitments: the gap between models and decisions, and instance-level reasoning. Just as the LendingClub case shows that prediction accuracy alone is insufficient for investment decisions, the Facebook Likes case shows that model accuracy alone is insufficient for ethical deployment—users and stakeholders need to understand *which evidence drove this specific decision*. The 2026 extension to generative AI prompt-counterfactuals signals that Provost sees this framework as generalizable beyond classification to any system where inputs combine to produce consequential outputs.

---
*Part of the [[foster-provost|Foster Provost]] persona knowledge base*
