# Is an "X% replication rate" insightful or meaningless?

An interactive, single-file simulation of the argument in **Devezer & Buzbas (2026),
*"The Difference Between 'Replicable' and 'Not replicable' is not Itself Scientifically Replicable"*** ([arXiv:2604.26268](https://arxiv.org/abs/2604.26268)).

> **Beware:** co-generated with Claude Code and Codex, for personal exploration. Not fully reviewed.

👉 **Live page:** see the GitHub Pages link in the repo's *About* / Settings → Pages.

Move the sliders and watch when a reported replication percentage carries information about the
underlying science — and when it cannot, no matter how many studies you run.

## What's inside

Sections badged **"Reproduces the paper"** compute the paper's own formulas in the browser:
1. The irreducible variance floor `μ(1−μ)ρ` and effective sample size `mₑ = m/[1+(m−1)ρ]`
2. Discriminability of "high" vs "low" results (Fig. 1)
3. The headline rate across a project — the aggregation problem
4. Why heterogeneity ρ is invisible in one-verdict-per-study data (operational model, k=1)
5. RPP, SCORE, and Many Labs 4 in these terms

Sections badged **"Beyond the paper"** are extensions / complementary arguments, clearly labelled:
6. A stress-test map of when the rate *is* informative
7. A coin-purse analogy (fair vs rigged coins)
8. How a base rate × power model produces a low rate (an Ioannidis-style argument, *not* the paper's)

A built-in **validation table** checks the engine's output against the numbers printed in the paper.
The whole thing is one self-contained `index.html` — no dependencies, no build step, no data leaves your browser.

## Caveats

The artefact gives the paper its strongest form and then flags, in section 6, where the broad thesis is
contested (the variance floor is benchmark-model-specific; richer continuous data can recover ρ; a mixture
average is composition-dependent rather than meaningless). See that section for the balanced reading.

*Not affiliated with or endorsed by the paper's authors. Built as an educational tool.*
