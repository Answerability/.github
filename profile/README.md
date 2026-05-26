# Answerability

**An independent research practice analyzing how AI search systems retrieve, trust, and cite companies across buyer-intent queries.**

When a buyer asks ChatGPT, Claude, Gemini, Perplexity, or Grok to recommend a provider, some companies get named and most do not. Answerability studies why — and publishes the framework, the method, and the reference patterns in the open.

We are a written-research practice, not a SaaS product and not a monitoring dashboard. Every engagement produces a structured intelligence report. This organization holds the parts of the work that are meant to be public: the framework, reference implementations, and a sample of the method.

---

## The framework

*Answerability* is the composite a company earns across three independent pillars. Each is scored 0–100; the composite is **constrained by the weakest pillar, not the average**, because a citation requires all three at once.

| Pillar | The question it answers |
|---|---|
| **Content** | Do you have content that answers what buyers actually ask, in a form an engine can lift? |
| **Retrieval** | Can AI systems access, crawl, parse, and structurally understand that content? |
| **Trust** | When an engine has several candidate sources, does it treat yours as cite-worthy? |

The pillars are independent in two senses. *Technically*: fixing one does not predictably move the others. *Operationally*: a page can score high on two pillars and remain uncited because the third fails. We do not abbreviate the framework to an acronym.

The full, versioned method — prompt-set construction, five-engine capture, per-URL scoring, and stated limitations — is published so it can be inspected and cited.

---

## Repositories

| Repository | What it is |
|---|---|
| [**answerability-framework**](https://github.com/answerability/answerability-framework) | The public specification of the Content / Retrieval / Trust framework — definitions, the scoring model, and the per-pillar signals. The method, openly documented. |
| [**llms-txt-examples**](https://github.com/answerability/llms-txt-examples) | Reference `llms.txt` patterns and an annotated template, by business type. Copy-ready. |
| [**answerability-sample-report**](https://github.com/answerability/answerability-sample-report) | An anonymized walkthrough of the diagnostic method and what a report contains, mirroring the published methodology. |

---

## Principles

- **A method you cannot inspect is not a method.** The protocol is fixed, versioned, and human-reviewed; only the input changes per engagement.
- **We report observed co-occurrence, not declared ranking factors.** AI systems are non-stationary; findings describe patterns within a bounded sample, not universal rules.
- **Where this overlaps with technical SEO, it overlaps.** We do not invent novelty where none exists.

---

**Website:** [answerability.ai](https://answerability.ai) · **Method:** [answerability.ai/methodology](https://answerability.ai/methodology/) · **Working papers:** [answerability.ai/insights](https://answerability.ai/insights/)

**Elsewhere:** [LinkedIn](https://www.linkedin.com/company/answerability-ai) · [Wikidata](https://www.wikidata.org/wiki/Q139927039)

*Engagements are confidential under MNDA. Content published here is released for inspection and citation under the licenses noted in each repository.*
