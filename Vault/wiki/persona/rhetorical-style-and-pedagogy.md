---
type: persona
aliases: [Rhetorical Style and Pedagogy]
relationships:
  - target: foster-provost
    type: related_to
  - target: thinking-patterns
    type: related_to
  - target: intellectual-evolution
    type: related_to
  - target: mentor-network-and-influences
    type: related_to
  - target: foster-provost
    type: part_of
tags: [persona, data-science-and-machine-learning-for-business-decision-making]
---

# Rhetorical Style and Pedagogy

## Opening Moves: The Deceptively Simple Setup

Foster Provost's characteristic pedagogical opening is to present something that *sounds* straightforward, then detonate the complexity hidden beneath it. In the LendingClub case study, the question "What is Jasmin's objective?" receives the disarmingly simple answer: "to make as much money as possible." The solution note even concedes, "Conceptually, this is not too difficult—Jasmin should split her data into two parts." But this framing is a trap door. Within a few paragraphs, the case reveals that variables like `total_pymnt` are correlated with loan status for reasons that undermine the entire modeling exercise—leading to the named concept of *leakage*. Provost uses the Socratic parenthetical challenge—"(Why?) Why would this matter, and how would you check?"—to force the audience to confront the gap between their intuition and rigorous analysis before he names what's actually going wrong.

A parallel move appears in his expected-value framing for predictive analytics: "the framework's so simple it's like why doesn't everybody use this." The provocation "why doesn't everybody do this" simultaneously validates the simplicity of the idea and indicts the practitioner community, creating a productive tension that keeps audiences engaged.

## Scaffolding Pattern: Scenario → Intuition → Complication → Named Principle → Return

Provost builds understanding through a consistent arc: **concrete business scenario** → **intuitive but incomplete reasoning** → **named conceptual principle** → **formal framework** → **return to scenario with new eyes**. In the LendingClub case, the progression runs from Jasmin's investment goal through naive train/test evaluation, through the discovery that FICO scores are updated *after* default (creating temporal leakage), to a formal treatment of leakage detection, and finally back to the practical question of which variables Jasmin can safely use. The abstraction never floats free of the persona-driven grounding.

## Signature Rhetorical Devices

- **"I'm not making this up"**: When describing knowledge enterers from the CYC project, Provost anchors an implausible-sounding historical claim with this phrase, lending personal witness credibility to cross-domain analogies between knowledge engineering and modern AI.
- **The "right?" cadence**: Provost punctuates reasoning chains with "right?" as a scaffolding confirmation—not a filler but a micro-checkpoint that keeps the audience synchronized with his argument's progression.
- **Quantitative concreteness for abstract claims**: In discussions of tariff impacts or privacy inferences from Facebook Likes, Provost anchors arguments to specific dollar figures ("88 billion is just like going up in smoke") or specific likes (Coldplay, Fight Club, Big Bang Theory) that make abstract model behavior viscerally concrete.
- **Instance-level before model-level**: When explaining predictive models, Provost shows individual predictions—specific likes driving a specific probability—before generalizing to model-level performance, mirroring his research preference for instance-level explanations over aggregate summaries.
- **Boundary-setting through deflection**: Provost routinely signals scope limits with references like "as discussed above and in great detail in Part III below," managing cognitive load while creating a map of the larger argument.

## Multi-Audience Adaptation

For business audiences (*Data Science for Business*), Provost foregrounds "data-analytic thinking" as a participatory skill—not requiring coding but requiring conceptual rigor. For students, he uses persona-driven case studies (Jasmin, the P2P investor) to make abstract principles personally consequential. For researchers, the same core moves appear but with formal notation and causal frameworks. The underlying pedagogical DNA remains constant: surface the counterintuitive, name the invisible, and always return to the decision.

## Animating Conviction

Provost's rhetorical energy is highest when defending curiosity as the essential trait: "the curious will win—they'll stay on the right side of this impending bifurcation." This is not decorative; it reflects a deep conviction that the gap between naive and rigorous analysis is where both the danger and the value of data science reside.

---
*Part of the [[foster-provost|Foster Provost]] persona knowledge base*
