# Circular-Economy-as-a-Complex-Adaptive-System-Romania-and-Germany

## Overview

This project examines the circular economy from the perspective of complex adaptive systems, with a comparative focus on Romania and Germany. The analysis investigates how circularity-related indicators are associated with economic development and environmental pressure, and whether these relationships differ across economies at different stages of structural maturity.

Romania is used as the main case study, while Germany serves as a benchmark economy. The comparison is intended to highlight different adaptive trajectories, adjustment mechanisms, and sustainability dynamics within the European Union.

## Research objective

The main objective of the project is to analyze the degree of circularity and its relationship with economic development.

More specifically, the study aims to:

- evaluate the short-run and long-run effects of circular economy indicators on economic growth
- test whether resource efficiency and recycling are associated with economic development
- examine nonlinear relationships between growth, circularity, and environmental pressure
- interpret these dynamics through the lens of complex adaptive systems

## Conceptual framework

The project is grounded in the view that the economy can be understood as a complex adaptive system. In such a system, structural change emerges through nonlinear interactions, delayed feedback, adaptive responses, and regime shifts.

From this perspective:

- economic growth, circularity, and environmental pressure interact dynamically
- the same mechanisms may generate different outcomes depending on institutional and structural maturity
- sustainability transitions are gradual and path-dependent rather than linear

This framework is especially relevant for comparing Romania and Germany, as the two economies occupy different positions along the same broader trajectory of structural adaptation.

## Data

The dataset consists of annual time series for Romania and Germany covering the period 2001–2023.

The data were collected from the Eurostat database, using indicators associated with the Sustainable Development Goals (SDGs).

Dependent variable:

- GDP – real GDP per capita

Explanatory variables:

- RP – resource productivity
- RRMW – recycling rate of municipal waste
- DNGGE – domestic net greenhouse gas emissions per capita

To improve comparability and statistical stability, the variables expressed in absolute levels were transformed into logarithms:

- lnGDP
- lnRP
- lnDNGGE

In order to test nonlinear relationships consistent with the Environmental Kuznets Curve (EKC) and the Inverted Circularity Curve (ICC), the squared term of logged GDP per capita was also included:

- lnGDP2
  
## Software used

The econometric outputs presented in the case study document were generated in EViews. The project document combines the statistical results obtained in EViews with the economic interpretation developed in the written analysis.

## Methodology

### 1. ARDL modelling
ARDL models are estimated separately for Romania and Germany in order to examine short-run and long-run effects of circular economy indicators on economic growth.

The lag structure is selected automatically using the Akaike Information Criterion (AIC), subject to a restricted maximum lag length appropriate for the relatively small sample size.

### 2. Bounds cointegration test
The ARDL Bounds testing approach is used to determine whether a long-run equilibrium relationship exists between GDP per capita and the circular economy / environmental variables.

### 3. EKC and ICC testing
The Environmental Kuznets Curve (EKC) and Inverted Circularity Curve (ICC) hypotheses are tested through nonlinear ARDL specifications using `lnGDP` and `lnGDP2`.

This makes it possible to detect threshold effects and possible regime changes in the relationship between development, emissions, and circularity.

## Main findings

### Romania

The Romanian results suggest that economic growth remains only weakly linked to circular economy indicators in the long run. Resource productivity and municipal recycling do not show strong long-run effects on GDP per capita, while greenhouse gas emissions remain positively associated with growth in the short run, indicating incomplete decoupling between development and environmental pressure.

The EKC results support an inverted-U relationship between economic development and environmental degradation. Romania appears to have passed the estimated turning point, but the downward adjustment in emissions is still gradual and irregular.

The ICC results suggest that the circularity-growth relationship is still emerging and delayed, which is consistent with a transitional economy undergoing slow structural adaptation.

### Germany

In Germany, the relationship between growth and circular-economy-related efficiency is stronger and more coherent. Resource productivity has a positive and statistically significant effect on economic growth, especially in the long run, while recycling appears to be already structurally embedded.

The EKC pattern is also supported, but in a more mature and stabilized form. Germany appears to be firmly located on the downward side of the environmental Kuznets curve, where growth is increasingly associated with lower environmental pressure.

The ICC hypothesis is not confirmed for Germany, which can be interpreted not as an absence of circularity, but as evidence that circularity has already been internalized structurally and no longer varies systematically with GDP.

## Comparative interpretation

The results indicate that Romania and Germany represent different adaptive states within the same broad sustainability transition.

- Germany displays a more mature and coordinated structure, in which efficiency, institutional stability, and technological adaptation are more deeply integrated into growth dynamics.
- Romania shows a more gradual and delayed adjustment process, with stronger dependence on cyclical corrections and a weaker structural role of circular-economy mechanisms.

From a complex adaptive systems perspective, these differences do not imply divergent models of development, but rather different positions along the same path of structural adaptation.

## Repository structure

The repository includes the project document, the supporting datasets, and the README file.

- CircularEconomy.docx – project document in Romanian
- DateRO.xlsx – dataset for Romania
- DateDE.xlsx – dataset for Germany
- README.md – English description of the project

