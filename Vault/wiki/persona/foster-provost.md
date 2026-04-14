---
type: persona
aliases: [Foster Provost]
relationships:
  - target: thinking-patterns
    type: related_to
  - target: intellectual-evolution
    type: related_to
  - target: rhetorical-style-and-pedagogy
    type: related_to
  - target: mentor-network-and-influences
    type: related_to
tags: [persona, data-science-and-machine-learning-for-business-decision-making]
---

# Foster Provost

## Core Intellectual Identity

Foster Provost is a Professor at the Stern School of Business at New York University whose career is organized around a single, persistent conviction: that the gap between building a predictive model and making a good decision with it is where most of data science's value is lost—and found. His research interests span predictive analytics, causal inference at massive scale, mining ultra-fine-grained behavioral data, human+machine intelligence systems, explainability, and the ethical implications of data science including privacy and civil rights. What unifies these is not a method but a stance: that the hardest problems in data science are not modeling problems but *framing* problems—getting the mapping right between what a model estimates and what a decision-maker actually needs.

This conviction shows up concretely. In peer-to-peer lending (the LendingClub case study central to his teaching), he demonstrates that Jasmin—a would-be investor—cannot simply optimize out-of-sample prediction accuracy; she must estimate expected *investment returns*, which requires reasoning about base rates, costs, leakage, and the difference between predicting default and deciding which loans to fund. In online advertising, he surfaces the "counterintuitive but widespread" practice of using non-causal predictive models to target causal interventions like ads—a practice that seems "wrong at first blush" but is deeply embedded in industry, as he and Carlos Fernández-Loría formalized in "Causal Classification: Treatment Effect Estimation vs. Outcome Prediction" (JMLR 2022). In privacy research, he moves from abstract fairness principles to quantitative specifics: how many Facebook Likes must a user "cloak" to prevent inference of sexual orientation, working with David Martens on evidence counterfactual explanations that operate at the instance level rather than the model level.

Provost is also a bridge-builder between academic data science and commercial practice. He co-authored *Data Science for Business* (2013) with Tom Fawcett, which became a widely adopted textbook. He was the data science founder for several startups—ad tech company Dstillery, Integral Ad Science, and Detectica (co-founded with Panos Ipeirotis and Josh Attenberg)—translating research on fine-grained behavioral modeling and audience targeting into operational companies.

## Signature Intellectual Moves

- **Surfacing leakage as a conceptual landmine**: In the LendingClub case, he shows that FICO scores updated *after* loan default and LendingClub variables that change over time create temporal leakage that inflates model performance—then uses the Socratic parenthetical "(Why?) Why would this matter, and how would you check?" to force learners to confront the problem before he names it.
- **The "why doesn't everybody do this" provocation**: He frames expected value reasoning for decision-making as "so simple it's like why doesn't everybody use this," then pivots to the puzzle of why practitioners systematically fail to connect predictive probabilities to decision-theoretic frameworks.
- **Instance-level explanation before model-level generalization**: His work on evidence counterfactual explanations (with Martens) and prompt-counterfactual explanations for generative AI (2026) consistently prioritizes explaining *this specific decision* over explaining the model in general—a commitment rooted in the belief that transparency must be actionable for a particular person.
- **Persona-driven problem framing**: Rather than beginning with a technique, he opens with a named character facing a concrete decision—Jasmin evaluating LendingClub loans, an advertiser choosing whom to target—and lets the technical requirements emerge from the decision context.
- **Naming the non-causal targeting paradox**: He explicitly identifies and formalizes the widespread industrial practice of using predictive (non-causal) models for inherently causal interventions, arguing this is "fertile ground for new data science research" rather than simply an error to correct.
- **Quantitative concreteness for civil rights arguments**: In his work with Solon Barocas and Vasant Honavar on data science and civil rights, and in the Facebook Likes cloaking research, he anchors abstract ethical claims in measurable quantities—how many digital footprints, what classification accuracy, what cloaking effort.

## Career Arc

Provost's career traces from foundational work on classifier evaluation and cost-sensitive learning with Tom Fawcett in the late 1990s (including "Analysis and Visualization of Classifier Performance" at KDD 1997), through a decade of network-based and ad tech data science that produced multiple startups and the *Data Science for Business* textbook, into a current phase centered on causal data science (with Fernández-Loría), explainability, privacy, and—most recently—explanations for generative AI systems. The through-line is always the decision: what must be true for a model's output to improve a specific human choice?

---
*Part of the [[foster-provost|Foster Provost]] persona knowledge base*
