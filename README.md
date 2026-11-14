# Free Boundary Problems

This repository collects research manuscripts and drafts on the one-phase Bernoulli free boundary problem. Together the drafts establish rigidity of global classical stable solutions in dimensions five and six. The first manuscript proves that every global classical stable solution in $\mathbb{R}^5$ has zero Hessian in its positive phase, using an exact rational tensor certificate to obtain a curvature Caccioppoli inequality at power $39/10$, then combining the Fernández-Real–Serra free-boundary tree with a signed Neumann iteration and a five-dimensional Gaussian calibration. The second manuscript proves that every global classical stable solution in $\mathbb{R}^6$ is one-dimensional, using OpenAI's algebraic certificate to exclude nonflat smooth stable cones in dimensions five and six, then applying the Fernández-Real–Serra blow-down theorem together with a local gradient-defect estimate. Both results contribute to the program of classifying stable solutions to the one-phase Bernoulli problem in low dimensions.

**Draft status:** All manuscripts present candidate proofs. The team is continuing to verify every argument. The summaries below describe the statements and proofs as currently drafted.

* * *

## Manuscripts

### 1. Global classical stable solutions of the one-phase Bernoulli problem in dimension five

**[Read the PDF](https://github.com/mingfeng87/Free-Boundary/blob/main/stable_bernoulli_rigidity_dimension_five.pdf)**

| Detail | Value |
|---|---|
| **Dimension** | $5$ |
| **Range** | Global classical stable solutions |
| **Length** | 65 pages |

The manuscript proves that every global classical stable solution of the one-phase Bernoulli problem in $\mathbb{R}^5$ has zero Hessian in its positive phase. An exact rational tensor certificate yields a curvature Caccioppoli inequality at power $39/10$. Combined with the selected free-boundary tree of Fernández-Real and Serra, summation over all active tree pieces gives an $L^{6/5}$ Hessian estimate with the full power of the selected excess. A weighted cutoff transfers that power to the higher curvature moment, and the resulting neck estimate lowers the critical selection exponent to $11/18$ while bounding each relevant neck radius by $C\varepsilon^{12/11}R$. These gains allow the signed Neumann iteration to reach the amplitude scale, and a five-dimensional Gaussian calibration then contradicts the logarithmic excess lower bound. The dimension-dependent calculations, the multiplier in ordinary tensor notation, and the complete rational factor data are provided in an electronic supplement; the scalar-weight and boundary inequalities are proved analytically, while the full interior inequality is established by exact rational reconstruction and is therefore computer-assisted. The draft status note states that the candidate proof was obtained on November 7, 2026, through extensive dialogue-based training with AI and is currently under verification.

* * *

### 2. Global stable solutions of the one-phase Bernoulli problem in dimension six

**[Read the PDF](https://github.com/mingfeng87/Free-Boundary/blob/main/stable_bernoulli_dimension_six.pdf)**

| Detail | Value |
|---|---|
| **Dimension** | $6$ |
| **Range** | Global classical stable solutions |
| **Length** | 49 pages |

The manuscript proves that every global classical stable solution of the one-phase Bernoulli problem in $\mathbb{R}^6$ is one-dimensional. OpenAI's algebraic certificate, checked by exact rational computation, excludes nonflat smooth stable cones in dimensions five and six. This allows the Fernández-Real–Serra blow-down theorem to be applied, yielding mean-square gradient closeness to two-sided linear profiles on large balls for a hypothetical nonflat solution. A local gradient-defect estimate converts the averaged error into a supremum bound for the defect, and the direction-independent length defect then vanishes at each fixed point, giving $|Du| = 1$ in the positive phase. Harmonicity then gives $D^2u = 0$. The manuscript also obtains local curvature bounds and axial symmetry for finite-index solutions. The draft status note states that the candidate proof was obtained on November 7, 2026, through extensive dialogue-based training with AI and is currently under verification.

* * *

## Citing a manuscript

Use the full manuscript title and the date printed in the PDF, use M. Zhao et al. as the author of PDF files. Include the [repository URL](https://github.com/mingfeng87/Free-Boundary) and the commit hash or a commit-specific PDF link for the version consulted, so that the cited draft can be identified after revisions.

* * *

## Repository structure

| File | Description |
|---|---|
| [`stable_bernoulli_rigidity_dimension_five.pdf`](https://github.com/mingfeng87/Free-Boundary/blob/main/stable_bernoulli_rigidity_dimension_five.pdf) | Dimension 5, zero Hessian rigidity for stable solutions |
| [`stable_bernoulli_dimension_six.pdf`](https://github.com/mingfeng87/Free-Boundary/blob/main/stable_bernoulli_dimension_six.pdf) | Dimension 6, one-dimensional symmetry for stable solutions |

* * *

## Keywords

One-phase Bernoulli problem; stable solutions; free boundary; rigidity; curvature estimates; neck decomposition; exact algebraic certificate; blow-down; gradient defect; finite-index solutions.
