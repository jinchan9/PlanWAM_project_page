# PlanWAM Website

Anonymous ICLR 2027 project page for the current manuscript in `PlanWAM_Latex/iclr2027/iclr2027_conference.tex`.

> PlanWAM: Planning-Shaped Future Representations for End-to-End Autonomous Driving

## Page Structure

- **Overview** states the planning-shaped representation question and the headline results: 93.8 PDMS, 90.9 EPDMS, 38.7 HD-Score, and 53.7 Route Completion.
- **Motivation** contrasts pixel reconstruction, latent prediction, future-conditioned planning, and PlanWAM.
- **Method** covers the Temporal Register Pyramid, the planning-shaped posterior, Hindsight-to-Foresight Distillation, foresight-conditioned planning, and the two-stage objectives. It includes the three-transformer data flow.
- **Experiments** reports NAVSIM-v1, NAVSIM-v2, and zero-shot HUGSIM, including how the HUGSIM average is weighted.
- **Ablations** covers components, future representation, latent usage, temporal allocation, distillation, and the failure analysis.
- **Further analysis** adds the appendix studies: posterior query role, future duration, distillation weight, and trainable modules.
- **Citation** is an anonymous BibTeX entry.

## Local Entry Points

- `index.html` is the project page.
- `src/iclr2027_conference.pdf` is the Paper button, copied from the current LaTeX build.
- `https://anonymous.4open.science/w/PlanWAM-4BF4/` is the Code button, matching the reproducibility statement.

## Figures

Paper figures used on the page live in `src/figures/`:

- `introduction.png`: four future-modeling paradigms.
- `framework.png`: prior/posterior training and history-only inference.
- `compression.png`: Temporal Register Pyramid.
- `architecture.png`: world-model, planner, and scorer transformers.
- `benchmark.png`: NAVSIM and HUGSIM qualitative results.
- `failure-analysis.png`: failure-type distribution and reduction attribution.

The failure caption follows the figure and the manuscript's Chinese note: NC / TTC / DDC drop by 62.3% / 62.4% / 66.7%. The English paragraph currently writes the TTC drop as 52.4%; confirm which value should stand.

Clicking a figure opens the enlarged-image viewer.
