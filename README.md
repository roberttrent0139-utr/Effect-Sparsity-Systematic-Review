# A Systematic Mapping Review of Effect Sparsity in Experimental Design

### Evaluating When Main-Effect Models Break Down in Complex Systems

**Author:** Robert Trent  
**Program:** M.S. Applied Mathematics, West Texas A&M University  
**Date:** July 2025 (Capstone Project)

---

## Overview

The principle of **effect sparsity** — the assumption that system behavior is driven primarily by main effects and low-order interactions — is foundational to modern experimental design. But when does this assumption become invalid?

This systematic mapping review, guided by PRISMA standards, searched for established criteria to determine when practitioners should abandon the sparsity assumption in favor of models incorporating higher-order interactions. The review synthesized literature across **five disciplines**: statistics, psychology, economics, engineering, and complexity science.

**The central finding:** No universal framework exists. Instead, the review uncovered a profound schism between the theoretical imperative from complexity science to model higher-order interactions and the practical statistical traditions built upon their exclusion.

## The Problem

Unlike physics, where clear thresholds dictate model transitions (e.g., relativistic corrections become necessary when velocity exceeds ~10% of the speed of light), experimental design offers **no analogous criteria** for when simplified models become misleading. Practitioners are left to guess whether their system requires higher-order interaction terms — a gap with real consequences for scientific reproducibility.

## Methodology

| Component | Detail |
|-----------|--------|
| **Framework** | PRISMA-guided systematic mapping review |
| **Databases searched** | Google Scholar, IEEE Xplore, PubMed |
| **Initial records identified** | 36,358 |
| **Records screened** | 8,358 (after deduplication and initial filtering) |
| **Full-text articles assessed** | 84 |
| **Studies included** | 17 (9 from database search + 8 from citation searching) |
| **Citation methods** | Backward snowballing + forward citation tracking |
| **Search period** | June 4–14, 2025 |

The high exclusion rate (98.8% at title/abstract screening) reflects both the breadth of initial search terms and the **specificity of the research question** — itself evidence of the limited interdisciplinary dialogue the review investigates.

## Key Findings

The literature organized into three thematic streams, each operating largely in parallel without cross-disciplinary synthesis:

### 1. Applied Heuristics & Empirical Warnings
- **Muralidharan et al. (2025):** Re-analysis of 27 factorial experiments from top economics journals found that **53% of previously significant main effects lost significance** when interactions were properly modeled
- **Jankovic et al. (2021):** Controlled computational experiments (~500,000 simulation runs) demonstrated that interaction-capable designs significantly outperformed main-effects-only screening designs in complex building energy systems

### 2. The Methodological Debate on Unreplicated Designs
- Decades-long statistical effort to formalize analysis when replication is impossible (MSE = 0/0)
- Traced the evolution from Lenth's PSE (1989) through simulation-based corrections (Ye & Hamada, 2000) to Bayesian frameworks (Chipman et al., 1997)
- **Critical finding:** All methods are sophisticated tools for working *within* the sparsity assumption — none question whether the assumption itself is valid for a given system

### 3. The Theoretical Imperative from Complex Systems
- **Battiston et al. (2021), Zhang et al. (2023):** Mathematical proof that for certain network architectures, higher-order interactions are the *primary drivers* of collective behavior, not negligible noise
- Establishes a structural criterion: if a system's architecture is best represented as a higher-order network, the sparsity principle is **theoretically invalid**

## Central Argument

Effect sparsity has migrated from a **pragmatic tool** for resource-constrained unreplicated designs into a **pervasive, unexamined ideology**. This creates what the paper terms "statistical epicycles" — models that are mathematically convenient but theoretically flawed, producing contextually fragile findings that contribute to the broader replication crisis.

The paper argues for a "third way" rooted in the **primacy of theory**: fields studying complex systems must develop their own domain-specific criteria for interaction modeling rather than importing reductionist tools designed for simpler systems.

## PRISMA Flow Summary

```
Records identified (databases):     36,358
  ├─ Duplicates removed:             ~4,200
  ├─ Records removed (other):       ~22,800
  └─ Records screened:                8,358
      ├─ Excluded at title/abstract:  8,258
      └─ Full-text sought:              100
          ├─ Not retrieved:               16
          └─ Assessed for eligibility:    84
              ├─ Excluded:                75
              └─ Included (database):      9

Records identified (citation search):   8
  └─ All 8 included after assessment

Total included studies:                 17
```

## Disciplines Covered

The 17 included sources span: statistical methodology (Technometrics, Statistica Sinica), physics (Nature Physics, Nature Communications), economics (Review of Economics and Statistics), engineering (Energy and Buildings), biology/philosophy of science (EMBO Reports, Theory in Biosciences), and meta-science (PNAS, Science, Psychological Science).

## Selected References

- Battiston, F., et al. (2021). The physics of higher-order interactions in complex systems. *Nature Physics*, 17(10), 1093–1098.
- Chipman, H., Hamada, M., & Wu, C. F. J. (1997). A Bayesian Variable-Selection Approach for Analyzing Designed Experiments. *Technometrics*, 39(4), 372–381.
- Lenth, R. (1989). Quick and Easy Analysis of Unreplicated Factorials. *Technometrics*, 31(4), 469–473.
- Muralidharan, K., Romero, M., & Wüthrich, K. (2025). Factorial Designs, Model Selection, and (Incorrect) Inference in Randomized Experiments. *Review of Economics and Statistics*, 107(3), 589–604.
- Ye, K. Q., & Hamada, M. (2000). Critical Values of the Lenth Method for Unreplicated Factorial Designs. *Journal of Quality Technology*, 32(1), 57–66.
- Zhang, Y., Lucas, M., & Battiston, F. (2023). Higher-order interactions shape collective dynamics differently in hypergraphs and simplicial complexes. *Nature Communications*, 14(1), 1605–1608.

Full reference list of all 17 included studies plus supporting sources available in the complete paper.

## Availability

The full 41-page paper including appendices (GLM derivations, Lenth's PSE worked example) is available upon request.

## Author

**Robert Trent**  
M.S. Applied Mathematics, West Texas A&M University  
B.S. Biomedical Science, Texas Tech University  
Contact: robert.trent0139@gmail.com
