# Migration Prospects and Human Capital Formation in Europe

## Overview

This project examines whether the prospect of working in other EU countries influenced educational outcomes among students in Central and Eastern European countries following the 2004 EU enlargement.

The analysis uses student-level data from the OECD Programme for International Student Assessment (PISA) and a Difference-in-Differences (DiD) approach to compare changes in educational performance between selected accession countries and a control group.

## Research Question

**Did the prospect of increased labour mobility following the 2004 EU enlargement affect student performance in accession countries?**

## Data

The analysis uses data from four PISA waves:

- **Years:** 2000, 2003, 2006 and 2009
- **Geographic scope:** European countries
- **Outcomes:** Mathematics, reading and science scores

The treatment group consists of four countries that joined the European Union in 2004:

- Poland
- Czech Republic
- Hungary
- Latvia

The 2000 and 2003 waves provide pre-enlargement observations, while the 2006 and 2009 waves capture educational outcomes after accession.

## Empirical Strategy

The effect is estimated using a Difference-in-Differences model with country and year fixed effects:

\[
Y_{ict} = \beta DID_{ct} + \gamma X_{ict} + \alpha_c + \lambda_t + \epsilon_{ict}
\]

Here, \(Y_{ict}\) represents the educational performance of student \(i\) in country \(c\) and year \(t\). The coefficient \(\beta\) captures the estimated difference in post-enlargement outcomes between the treatment and control groups.

The model includes student-level controls for gender, socioeconomic background (ESCS), household wealth and other household characteristics. Country and year fixed effects account for persistent differences between countries and common changes over time. Standard errors are clustered at the country level.

## Robustness Check

The baseline results are compared with estimates based on a control group restricted to neighbouring European countries. This provides a check on whether the findings are sensitive to the choice of comparison countries.

## Tools and Methods

**Tools**
- Python
- pandas
- statsmodels
- matplotlib

**Methods**
- Difference-in-Differences regression
- Country and year fixed effects
- Clustered standard errors
- Robustness analysis

## References

- Beine, M., Docquier, F., & Rapoport, H. (2008). *Brain drain and human capital formation in developing countries.*
- Batista, C., Lacuesta, A., & Vicente, P. (2012). *Testing the "brain gain" hypothesis: Micro evidence from Cape Verde.*
- Docquier, F., & Rapoport, H. (2012). *Globalization, brain drain, and development.*
- Mountford, A. (1997). *Can a brain drain be good for growth in the source economy?*
- Stark, O., Helmenstein, C., & Prskawetz, A. (1997). *A brain gain with a brain drain.*