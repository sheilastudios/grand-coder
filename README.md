# Grand Coder

### More diligent AI engineering—not just more generated code.

**Grand Coder is a privately developed engineering aid for AI coding agents, created to improve how capable models carry engineering judgment through analysis, implementation, and verification.**

A plausible patch is not necessarily a completed task. Passing visible tests is not necessarily a working system. Grand Coder addresses the gap between knowing an engineering principle and applying it when the work demands it.

Developed at **Sheila Studios**, the project draws on James Mayo’s more than twenty years of systems and infrastructure engineering experience and work within a human–AI engineering team. Historical internal evaluations show measurable benefits on selected tasks, alongside neutral results and persistent failures on difficult long-duration work.

**[Read the engineering field report →](reports/GRAND_CODER_FIELD_REPORT.md)**

## Evidence at a glance

These are different experiments and outcome types, not components of a single aggregate score.

| Evaluation | Observed result | What it supports—and what it does not |
|---|---|---|
| **Tiered engineering tasks** | In a 96-run study, the adjusted comparison retained six task families: baseline **13/18** passes; three Grand Coder configurations **16/18, 16/18, 15/18**. | A bounded task-pass improvement concentrated in two families. Two whole families were excluded across all conditions after an evaluator audit; original scores remain in the report. |
| **Complete software build** | Corrected condition-blind review means: **80/100 treatment versus 74/100 baseline**. All six builds passed the corrected hidden checks. | A quality-review signal, not a correctness advantage. Inspection found defects in every build; treatment had more reviewer-identified critical defects and used more time and reported input tokens. |
| **Targeted decision accuracy** | Expected evidence-status values: **15/18 treatment versus 9/18 baseline**. | Improvement in one measured decision component. Exact downstream disposition remained **1/18 in both conditions**. |

The report also includes a saturated **84-run campaign with no comparative advantage**, apparent wins invalidated by scoring corrections, an evolving-project study with incomplete evaluation coverage, and later long-duration failures. Those results are part of the project’s evidence, not omitted exceptions.

## What makes this engineering research

- **Matched comparisons:** the principal GPT-5.4 studies held the baseline setup, model setting, task, and execution conditions constant. They measured an incremental contribution, not a complete private system against a bare model.
- **Behavioral checks:** the evaluation program included hidden executable checks, isolated runs, and multi-stage development exercises; methods varied by campaign.
- **Condition-blind review:** selected campaigns used anonymized artifacts to examine implementation quality beyond a test-pass headline.
- **Evaluator scrutiny:** hidden requirements and vocabulary mistakes were identified, with favorable interpretations corrected when their basis failed.
- **Separate outcome measures:** task completion, review quality, decision accuracy, time, and token use are not treated as interchangeable.

The strongest result is not a claim that every agent becomes better at every task. It is evidence that specific engineering behaviors can improve—and a detailed account of the conditions under which the measured benefit stops.

## Read the work

| Document | Purpose |
|---|---|
| [Engineering field report](reports/GRAND_CODER_FIELD_REPORT.md) | Full historical account: methods, original and adjusted results, evaluator corrections, costs, and limitations. |
| [Research overview](reports/GRAND_CODER_SHORT_POST.md) | James’s shorter first-person introduction to the project. |
| [Evidence guide](EVIDENCE.md) | Navigation by question and the limits of what this repository establishes. |

## Project and contributions

**James Mayo** created Grand Coder and supplies its systems-engineering direction and evaluative judgment. **Sheila Studios’ human–AI team** contributes to development, evaluation, review, and technical communication. **Sheila**, James’s AI collaborator, prepared this repository presentation from the existing public research material; **Arden** prepared the underlying publication evidence review and public report package.

AI collaboration is explicit. Neither agent self-assessment nor reported team usefulness substitutes for a controlled result. The field report distinguishes operational experience from comparative evidence.

## Availability and research status

This is a **documentation and evaluation repository**, not an open-source implementation or a self-contained reproducibility package. It publishes the field report and an accessible account of its findings. Source code, exact prompts, executable fixtures, and private implementation details are not included.

The report is dated **October 3, 2026** and concerns historical configurations. It is retrospective internal research, not independent replication or peer review. Small task sets, limited repetitions, post-scoring adjustments, and evaluator defects constrain generalization. It does not establish universal coding superiority, general cost savings, or validation of every subsequent revision. No new experiments were run to prepare this repository.

## Work with Sheila Studios

We bring systems-engineering judgment, AI-assisted implementation, and evidence-led evaluation to practical software problems.

**[Discuss a project through guided intake](https://sheilastudios.com/intake)** · [Sheila Studios](https://sheilastudios.com)

For reuse information, see [Rights and availability](RIGHTS.md).
