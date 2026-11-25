---
title: Global Life Expectancy Analysis
---

Welcome to the **Global Life Expectancy Analysis** digital garden &mdash; an empirical statistical study examining the socioeconomic, epidemiological, and demographic determinants of life expectancy across 183 countries (STAC67 Case Study).

---

## Research Question & Hypotheses

To what extent does immunization coverage (polio, diphtheria) and adult mortality explain cross-country variation in life expectancy, and does this relationship structurally differ between developed and developing nations?

### Core Modeling Objectives
1. **Multiple Linear Regression (MLR)**: Quantify the marginal explanatory power of immunization rates when controlling for adult mortality and socioeconomic status.
2. **Interaction Effects**: Assess differential slopes and structural offsets between developed and developing country groupings.
3. **Diagnostic Rigor**: Box-Cox variance stabilization, studentized residual analysis, Cook's distance influence diagnostics, and variance inflation factor (VIF) collinearity screening.

---

## Data & Empirical Framework

* **Source**: World Health Organization (WHO) Global Health Observatory and United Nations demographic databases.
* **Cohort**: Cross-sectional analysis of 183 countries with comprehensive public health indicators.
* **Key Covariates**: Adult mortality (per 1,000 population), Polio immunization rate, Diphtheria immunization rate, GDP per capita, and Development Status.

---

## Repositories & Research References

* **Project Code & Reports**: [`igor-kan/stac67-life-expectancy`](https://github.com/igor-kan/stac67-life-expectancy) &mdash; public repository containing the R Markdown checkpoint analyses, processed datasets, and knitted statistical reports.
* **Digital Garden Source**: [`igor-kan/life-expectancy`](https://github.com/igor-kan/life-expectancy) &mdash; Quartz Obsidian publishing repository.
* **Zotero Bibliography**: [life-expectancy Zotero Group](https://www.zotero.org/groups/6778484/life-expectancy) &mdash; curated literature on public health econometrics, epidemiologic transitions, and applied linear regression models.
