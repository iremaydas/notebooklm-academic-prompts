# NotebookLM Prompts for Academic Articles

A prompt library for reading academic articles with NotebookLM.

This repository is designed for anyone who reads academic papers and wants structured help with:

* understanding methods and research design
* identifying theoretical frameworks
* clarifying contributions and “so what?” value
* generating critical questions
* preparing article notes 

---

## How to Use This Repository

1. Upload an academic article, book chapter, or working paper to NotebookLM.
2. Choose the prompt that best matches your reading goal.
3. Copy the prompt text.
4. Paste it into NotebookLM.
5. Ask follow-up questions when needed.
6. Save useful answers.

---

## Prompt Index

### Start Here

| Prompt                                                       | Use it when you want to...                                       |
| ------------------------------------------------------------ | ---------------------------------------------------------------- |
| [All-Purpose Prompt](prompts/all-purpose.md)                 | understand an article when you do not know where to start        |
| [Article Overview](prompts/article-overview.md)              | get a structured first summary of an article                     |
| [Short Summary](prompts/short-summary.md)                    | create a quick 250–300 word summary                              |
| [What Should I Remember?](prompts/what-should-i-remember.md) | create a memory-friendly summary for later                       |

---

### Understanding Difficult Articles

| Prompt                                                                          | Use it when you want to...                                             |
| ------------------------------------------------------------------------------- | ---------------------------------------------------------------------- |
| [Explain Like I’m New to This Literature](prompts/explain-new-to-literature.md) | understand a difficult or unfamiliar literature                        |
| [Theory and Framework](prompts/theory-and-framework.md)                         | understand the theoretical argument of an article                      |
| [Causal Mechanism](prompts/causal-mechanism.md)                                 | understand how the article explains the link between cause and outcome |
| [Contribution](prompts/contribution.md)                                         | understand why the article matters                                     |

---

### Methods

| Prompt                                                                    | Use it when you want to...                                                                |
| ------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------- |
| [Methods and Research Design](prompts/methods-and-research-design.md)     | analyze the article’s method, data, and research design                                   |
| [Methods Translation](prompts/methods-translation.md)                     | translate a difficult methods section into plain language                                 |
| [Experiment Details](prompts/experiment-details.md)                       | understand experiment                                                                     |
| [Table and Figure Interpretation](prompts/table-figure-interpretation.md) | interpret models, tables, figures, coefficients, and results                              |

---

### Critical Reading and Evaluation

| Prompt                                                | Use it when you want to...                                                |
| ----------------------------------------------------- | ------------------------------------------------------------------------- |
| [Critical Evaluation](prompts/critical-evaluation.md) | evaluate strengths, weaknesses, limitations, and alternative explanations |

---

### Literature Review and Synthesis

| Prompt                                                            | Use it when you want to...                                     |
| ----------------------------------------------------------------- | -------------------------------------------------------------- |
| [Literature Review Notes](prompts/lit-notes.md)                   | turn an article into structured notes for a literature review  |
| [Compare Multiple Articles](prompts/compare-multiple-articles.md) | compare several uploaded articles and synthesize them together |

---

## Suggested Reading Workflow

### For a quick first read

Use these prompts in order:

1. [Article Overview](prompts/article-overview.md)
2. [Contribution / So What?](prompts/contribution.md)
3. [What Should I Remember?](prompts/what-should-i-remember.md)

---

### For a methods-heavy article

Use these prompts in order:

1. [Methods and Research Design](prompts/methods-and-research-design.md)
2. [Methods Translation](prompts/methods-translation.md)
3. [Table and Figure Interpretation](prompts/table-figure-interpretation.md)
4. [Critical Evaluation](prompts/critical-evaluation.md)

---

### For an experiment-based article

Use these prompts in order:

1. [Article Overview](prompts/article-overview.md)
2. [Experiment Details](prompts/experiment-details.md)
3. [Causal Mechanism](prompts/causal-mechanism.md)
4. [Critical Evaluation](prompts/critical-evaluation.md)

---

### For a theory-heavy article

Use these prompts in order:

1. [Explain Like I’m New to This Literature](prompts/explain-new-to-literature.md)
2. [Theory and Framework](prompts/theory-and-framework.md)
3. [Causal Mechanism](prompts/causal-mechanism.md)
4. [Contribution / So What?](prompts/contribution.md)

---

### For literature review work

Use these prompts in order:

1. [Article Overview](prompts/article-overview.md)
2. [Literature Review Notes](prompts/lit-notes.md)
3. [Compare Multiple Articles](prompts/compare-multiple-articles.md)
4. [What Should I Remember?](prompts/what-should-i-remember.md)

---

## Repository Structure

```text
notebooklm-academic-prompts/
│
├── README.md
│
└── prompts/
    ├── all-purpose.md
    ├── article-overview.md
    ├── causal-mechanism.md
    ├── compare-multiple-articles.md
    ├── contribution.md
    ├── critical-evaluation.md
    ├── experiment-details.md
    ├── explain-new-to-literature.md
    ├── lit-notes.md
    ├── methods-and-research-design.md
    ├── methods-translation.md
    ├── short-summary.md
    ├── table-figure-interpretation.md
    ├── theory-and-framework.md
    └── what-should-i-remember.md
```
