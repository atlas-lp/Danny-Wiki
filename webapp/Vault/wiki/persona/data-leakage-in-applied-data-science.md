---
type: persona
aliases: [Data Leakage in Applied Data Science]
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

# Data Leakage in Applied Data Science

Provost treats data leakage not as a technical footnote but as one of the most dangerous and pervasive threats in applied data science — a conceptual landmine that undermines both model building and model evaluation simultaneously. His distinctive framing is that leakage is *insidious* precisely because it inflates performance metrics in ways that make flawed models look excellent, meaning the standard safeguard of out-of-sample evaluation fails to catch it.

## The Non-Obvious Claim

The naive view is that splitting data into training and test sets protects against overfitting and provides honest evaluation. Provost's core teaching point is that leakage "often affects both the training and evaluation" — it poisons the test set just as thoroughly as the training set. A model built on leaked features will show stellar test-set performance, giving practitioners false confidence. This makes leakage categorically different from ordinary overfitting and far harder to detect through standard workflows.

## The LendingClub Case as Canonical Example

In the peer-to-peer lending case study developed with Cohen, Guetta, and Jiao ("Data-Driven Investment Strategies for Peer-to-Peer Lending," 2018), Provost uses the character Jasmin — an investor trying to build a data-driven lending strategy — to surface leakage through concrete discovery. The pedagogical sequence is carefully scaffolded:

1. **Observation as hook:** Students notice that `total_pymnt` is strongly correlated with loan status. Provost poses the Socratic parenthetical: "(Why?) Why would this matter, and how would you check?"
2. **Naming the invisible concept:** The correlation exists because total payment is *updated after* the loan outcome is determined. Using it in a predictive model means the model has access to information from the future — temporal leakage.
3. **Escalation to the harder case:** FICO scores present a subtler version. If a borrower defaults, their FICO score drops. A static dataset snapshot captures the *post-default* FICO score, making it "highly indicative of the outcome" for reasons that have nothing to do with predictive signal available at loan issuance. Provost notes explicitly: "Detecting this form of leakage is difficult given a static data set."
4. **The remedy:** "The best method to eliminate leakage is to obtain data from the time point and context" at which the prediction would actually be made — i.e., reconstruct the information state of the decision-maker at decision time.

## Diagnostic Framework

Provost offers a practical two-part diagnostic: (1) high correlation with the target variable is a useful but imperfect signal, and (2) the definitive check is whether each variable's value was available *at the time the prediction would be deployed*. This temporal reasoning — reconstructing what was knowable when — is the core intellectual operation.

## Connection to Broader Intellectual Project

Leakage connects directly to Provost's central theme of the gap between predictive models and actionable decisions. A leaked model produces predictions that cannot generalize to the actual decision context because the information environment at deployment differs from the information environment in the training data. This is structurally parallel to his work on why non-causal models fail when used for causal targeting interventions: in both cases, the model's apparent performance does not translate to the real-world setting where decisions must be made. Leakage is, in Provost's framing, the first and most fundamental way that a data science project can silently divorce itself from business reality.

---
*Part of the [[foster-provost|Foster Provost]] persona knowledge base*
