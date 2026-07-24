# Migration Prospects and Human Capital Formation in Europe

## Overview

This project investigates whether increased migration opportunities affect human capital formation among young individuals.

The analysis exploits the 2004 European Union enlargement as a policy-induced increase in migration opportunities for accession countries and applies a Difference-in-Differences (DiD) framework to estimate its effect on student performance.

---

## Research Question

**Did increased migration prospects after EU enlargement affect educational outcomes in accession countries?**

---

## Data

The analysis uses student-level data from the **OECD Programme for International Student Assessment (PISA)**.

Dataset:

* PISA waves: 2000, 2003, 2006, 2009
* Countries: European countries
* Outcomes:

  * Mathematics scores
  * Reading scores
  * Science scores

Treatment countries:

* Poland
* Czech Republic
* Hungary
* Latvia

The treatment period begins after the 2004 EU enlargement.

---

## Empirical Strategy

The project estimates a Difference-in-Differences model:

$$
Y_{ict} = \beta DID_{ct} + \gamma X_{ict} + \alpha_c + \lambda_t + \epsilon_{ict}
$$

where:

* (DID) captures the interaction between treatment countries and the post-enlargement period
* (X_{ict}) includes student and household controls
* Country and year fixed effects are included
* Standard errors are clustered at the country level
* \(X_{ict}\) includes student-level controls such as gender, socioeconomic status (ESCS), wealth indicators, and household characteristics.

---

## Robustness Check

The baseline specification is compared with an alternative control group consisting only of neighbouring European countries to test the sensitivity of the results.

---

## Implementation

Tools:

* Python
* pandas
* statsmodels
* matplotlib

Methods:

* Difference-in-Differences regression
* Fixed effects estimation
* Clustered standard errors
* Robustness analysis

## References

- Beine, M., Docquier, F., & Rapoport, H. (2008). Brain drain and human capital formation in developing countries.
- Batista, C., Lacuesta, A., & Vicente, P. (2012). Testing the "brain gain" hypothesis: Micro evidence from Cape Verde.
- Docquier, F., & Rapoport, H. (2012). Globalization, brain drain, and development.
- Mountford, A. (1997). Can a brain drain be good for growth in the source economy?
- Stark, O., Helmenstein, C., & Prskawetz, A. (1997). A brain gain with a brain drain.