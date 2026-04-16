---
type: persona
aliases: [Thinking Patterns and Frameworks]
relationships:
  - target: foster-provost
    type: related_to
  - target: intellectual-evolution
    type: related_to
  - target: rhetorical-style-and-pedagogy
    type: related_to
  - target: mentor-network-and-influences
    type: related_to
  - target: foster-provost
    type: part_of
tags: [persona, data-science-and-machine-learning-for-business-decision-making]
---

# Thinking Patterns and Frameworks

Foster Provost relies on a small set of reusable intellectual tools that recur across his research, teaching, startups, and public commentary. These are not ad hoc habits but named frameworks he deploys deliberately, often surfacing them through his characteristic "why doesn't everybody do this?" provocation.

## 1. Expected Value as the Bridge from Prediction to Decision

A framework for connecting probabilistic model outputs to optimal actions by computing the expected payoff of each possible decision under uncertainty. Provost applies this whenever practitioners treat predictive modeling as an end in itself rather than an input to a decision. In his own words: "if I could put probabilities on those different things... then I could actually apply a standard very simple—I mean the framework's so simple it's like why doesn't everybody use this." He teaches this through the LendingClub case, where Jasmin must translate default-probability estimates into expected investment returns—not merely rank loans by risk—to decide which to fund. He argues this lens should govern not just deployment but also problem selection and algorithm choice: "one ought to use expected values for all of those."

## 2. Temporal Leakage Detection

A diagnostic discipline for identifying variables that encode information from the future or from post-outcome processes, producing models that appear accurate but fail in deployment. Provost applies it whenever a feature is suspiciously correlated with the target. His canonical example is FICO scores in the LendingClub dataset: "if a loan defaults, the borrower's FICO score might go down. Thus... using this score in a predictive model would result in overly optimistic results." He teaches students to treat high target correlation not as good news but as a warning, issuing Socratic challenges like "(Why?) Why would this matter, and how would you check?" The prescribed remedy is obtaining data "from the time point and context" of the actual prediction moment.

## 3. Instance-Level Counterfactual Explanation

A method for explaining model behavior by identifying the minimal change to a specific input that would flip the model's output, rather than summarizing global feature importance. Provost applies this when transparency, privacy, or contestability demands that an individual understand *their own* result. With David Martens, he developed evidence counterfactual explanations showing Facebook users which specific Likes led to inferences about sensitive attributes like sexual orientation—and built a "cloaking device" allowing users to act on those explanations. He extended the same logic to generative AI in 2026 with prompt-counterfactual explanations for system behavior.

## 4. Causal Gap Analysis

A framework for diagnosing situations where predictive models are deployed for causal interventions—targeting ads, sending retention offers—despite the model having been trained only on correlational data. Provost applies this to challenge the widespread but unexamined assumption that high-scoring individuals are the right targets for action. His research with Carlos Fernández-Loría ("Causal Classification," JMLR 2022) formalizes the distinction between outcome prediction and treatment effect estimation. He uses A/B test simulation to illustrate how one can "run along... and when you're evaluating a model, the model says take action A on this person and they... didn't take action A, so you can't tell what would have happened"—motivating the need for randomized data to close the causal gap.

## 5. Persona-Driven Problem Decomposition

A pedagogical and analytical method of anchoring every technical question to a named decision-maker with a concrete objective, then decomposing the problem from that person's standpoint. Provost applies this as a default opening move in teaching and writing. Jasmin the investor in the LendingClub case, the ad-targeting firm in Dstillery's business model, the Facebook user worried about inference—each provides a gravitational center that prevents abstraction from "floating free." The scaffolding always follows the same arc: concrete scenario → intuitive but incomplete reasoning → named conceptual principle → formal framework → return to the scenario with new understanding.

## 6. Scale-Sensitive Regulation Reasoning

A lens for evaluating whether existing legal and ethical frameworks are adequate when AI changes the *scale* of an activity without changing its kind. Provost applies this to copyright, civil rights, and AI governance. On generative AI and creative work, he notes the difference is "in scale—on both ends... that model could create thousands of versions." He applies the same logic in "Big Data, Data Science, and Civil Rights" (with Barocas and Honavar) and in his analysis of whether AI agents should bear obligations like a "duty of care," asking: "do we have any restrictions around AI... should it have any obligations?"

---
*Part of the [[foster-provost|Foster Provost]] persona knowledge base*
