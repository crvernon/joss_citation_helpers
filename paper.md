---
title: 'test: a test submission'
tags:
  - Python
authors:
  - name: Person A. One
    orcid: 0000-0000-0000-0000
    corresponding: true
    affiliation: 1
  - name: Person B. Two
    orcid: 0000-0000-0000-0001
    affiliation: 2
affiliations:
  - name: Place, Here, XX., XXX
    index: 1
  - name: Place, There, XX., XXX
    index: 2
date: 1 May 2024
bibliography: paper.bib
---

# Summary

Informational content.

# Statement of need

Stuff was reported [@vernon2023harmonized]. Also, @vernon2023harmonized reported other stuff.

| Key                | Analysis                            | Required Parameters  | Optional Parameters         |
| ------------------ | ----------------------------------- | -------------------- | --------------------------- |
| `kstest`           | Kolmogorov-Smirnov Test             | `vars`               | `group_vars`                |
| `shapiro`          | Shapiro-Wilks Test                  | `vars`               | `group_vars`                |
| `z_normal`         | Z-Skewness & Z-Kurtosis test        | `vars`               | `group_vars`                |
| `levene`           | Levene Test                         | `vars`, `group_vars` |
| `fmax`             | F<sub>max</sub> Test                | `vars`, `group_vars` |
| `chi2_contingency` | Chi-squared Test                    | `vars`               |
| `fisher`           | Fisher's Exact Test                 | `vars`               |
| `pearsonr`         | Pearson's r                         | `vars`               |
| `spearmanr`        | Spearman's rho                      | `vars`               |
| `kendallt`         | Kendall's tau                       | `vars`               |
| `ttest_ind`        | Independent Samples T-test          | `vars`, `group_vars` |
| `ttest_rel`        | Dependent Samples T-test            | `vars`               |
| `ttest_ind_trim`   | Yuen's Two Samples T-test           | `vars`, `group_vars` |
| `ttest_ind_welch`  | Welch's Two Samples T-test          | `vars`, `group_vars` |
| `mannwhitneyu`     | Mann-Whitney U Test                 | `vars`, `group_vars` |
| `brunner`          | Brunner-Munzel Test                 | `vars`, `group_vars` |
| `wilcoxon`         | Wilcoxon-Signed Rank Test           | `vars`               |
| `bootstrap`        | Boostrap Percentile Method          | `vars`               | `group_vars`                |
| `f_oneway`         | One-way ANOVA                       | `vars`, `group_vars` | `posthoc`, `posthoc_method` |
| `f_oneway_rm`      | One-way Repeated Measures ANOVA     | `vars`               | `posthoc`, `posthoc_method` |
| `kruskal`          | Kruskal-Wallis Test                 | `vars`, `group_vars` | `posthoc`, `posthoc_method` |
| `friedman`         | Friedman Test                       | `vars`               | `posthoc`, `posthoc_method` |
| `f_nway`           | N-way ANOVA                         | `vars`, `group_vars` | `posthoc`, `posthoc_method` |
| `f_nway_rm`        | N-way Mixed Repeated Measures ANOVA | `vars`, `group_vars` | `posthoc`, `posthoc_method` |
| `linearr`          | Linear Regression                   | `vars`               |
| `hier_linearr`     | Hierarchical Linear Regression      | `vars`               |
| `logisticr`        | Logistic Regression                 | `vars`               |
| `oneway_ancova`    | One-way ANCOVA                      | `vars`, `group_vars` |
| `rm_ancova`        | One-way Repeated Measures ANCOVA    | `vars`               |
| `cronbach`         | Calculating Cronbach's Alpha        | `vars`               |

# References