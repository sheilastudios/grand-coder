# Evidence guide

The [Grand Coder Engineering Field Report](reports/GRAND_CODER_FIELD_REPORT.md) is the substantive research document in this repository. The README is a summary, not additional experimental evidence.

## Find the relevant result

| Question | Field report section | Essential qualification |
|---|---|---|
| Did more engineering tasks pass? | Evaluation Results §3: Tiered engineering tasks | Original: baseline 15/24; configurations A/B/C 18/24, 19/24, 18/24. Adjusted: 13/18 versus 16/18, 16/18, 15/18. Exclusions were post-scoring and symmetric; improvement was concentrated in two families. |
| Did entire builds become correct? | §5: A complete build task | Corrected hidden checks tied. All implementations had material defects on inspection despite passing those checks. |
| Did it help with evolving requirements? | §6: An evolving project | Some directional benefits, but unequal executable-check denominators and a missing manifest prevented a valid planned final score. Only three trajectories per condition. |
| Did decision accuracy improve? | §7: Later targeted and long-duration testing | Status-field accuracy improved; downstream disposition did not. The later long-duration comparisons tested additions, not Grand Coder versus no Grand Coder. |
| Were there neutral results? | §1, §2, and §4 | Initial breadth was mostly neutral; the 84-run follow-up saturated; a targeted gate’s apparent advantage disappeared after semantic review. |
| Did it reduce cost? | §5 and Cost and Verification | No general cost-saving claim. One build study used approximately 19% more elapsed time and 27% more reported input tokens under treatment. Token totals are not direct billing estimates. |
| Can I reproduce these experiments here? | Disclosure and Scope | No. Private fixtures, prompts, implementation, and raw experiment records are not supplied. |

## How to interpret the numbers

- Repeated runs of one task are not independent task families.
- Checkpoints and hidden scenarios are not independent projects.
- Different historical configurations do not form a single replicated treatment.
- Review scores, test passes, and exact response fields measure different things.
- Operational usefulness is attributed team experience, not a measured productivity percentage.
- This packaging pass did not rerun the experiments or re-audit all private records.

The two report files preserve the existing public editions unchanged. The repository adds presentation and navigation, not new research results.
