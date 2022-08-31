## Prenatal Exposure to SARS and Birth Weight: Exploiting a Natural Experiment in Hong Kong

#### Research Statement 

- By exploiting SARS as an exogenous source of stress, this paper examines whether prenatal maternal exposure to such stress affects birth weight with the applicatin of OLS/ANOVA, Propensity Score Matching, and Bootstrapping.

#### Outline

- Introduction
- Background
  - SARS as a Public Health Crisis
  - Maternal Stress as Mechanisms
  - SARS as Exogenous Sources of Maternal Stress
- Literature Review
- Methods
  - Data
  - Variables
  - Models
    - Treat SARS as a Experiment (randomized)
      - OLS/ANOVA
    - Treat SARS as a Quasi-Experiment (non-randomized)
      - Propensity Score Matching
      - OLS/ANOVA
      - Bootstrapping
- Results
  - $Y_i = \alpha + \beta\space Treat + e_i$ where $\beta = E(Y_i^{Treatment} - Y_i^{Control})$ is the Average Treatment Effect (ATE) 
- Discussion and Conclusion

#### PDF Preview

https://github.com/mingzhao1103/Stata_SARS/blob/main/report.pdf



*NOTE*


Difference-in-Differences $(DID)$ is a quasi-experiment design that resembles a randomized experiment to learn about causal relationships: 

  - $Y = \beta_0 + \beta_1 \space Treat + \beta_2 \space Time + \beta_3 \space (Treat\*Time) + \beta_4 \space Covariates + e_i$ where $\beta_3$ captures $DID$, the treatment effect
       
  - $DID = (Treatment_{after} - Treatment_{before}) - (Control_{after} - Control_{before})$

  - Parallel Trends Assumption: the treatment group and the control group would follow equal trends over time in the absence of any treatment.



