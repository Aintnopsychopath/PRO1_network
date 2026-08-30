# Recovered-source inventory and reproduction gates

Audit date: 2026-08-30. File presence is not successful execution.

| Evidence | Location | Status |
|---|---|---|
| Original PDF | `PRO1_2024_Sep5.pdf`, main | Retained unchanged; results not reverified |
| Base-case notebook | `Step 1/Step 1 PW.ipynb`, `step_2` | Tracked source exists; local copy has uncommitted edits |
| Time-series notebook | `Step 2/Step 2 PW.ipynb`, `step_2` | Tracked source exists; local copy has uncommitted edits |
| Load shape | `Step 2/Loadshape_step_2.xlsx`, `step_2` | Source and redistribution terms need confirmation |
| Exported time series | `Step 2/time_series_results.xlsx`, `step_2` | Not a clean-run verification record |
| Later notebooks/profiles | Local untracked files | Not published or represented as submitted coursework |

Next steps, in order:

1. Confirm original authors/team contributions and course/input reuse permissions.
2. Preserve the original revision; map each report figure/table to cells, inputs and execution order.
3. Run recovered source in an isolated, pinned pandapower environment; record missing inputs and failures without inventing replacements.
4. Package a labelled reproduction only after mapping its relationship to the original study. Later reconstruction is not historical coursework code.
5. Implement explicit single-element line/transformer removal and record disconnected/nonconvergent contingencies separately from base-case overloads.
6. Compare regenerated values against the report with tolerances and a difference table. Unmatched results stay unresolved.
7. Add package/CLI, scientific tests, CI, attribution and an appropriately scoped licence after these gates pass.

No numerical equivalence, external validation, executable release, or new ownership assertion is made here.
