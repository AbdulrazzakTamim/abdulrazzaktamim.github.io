---
title: "Housing Subsidies for Refugees: Experimental Evidence on Life Outcomes and Social Integration in Jordan"
collection: publications
permalink: /publication/Subsidies
venue: 'National Bureau of Economic Research'
date: 2025-1-1
status: 'working'
layout: single
header:
  overlay_image: https://www.abdulrazzaktamim.com/images/publications/subsidies-header.png
  overlay_filter: 0.3
  caption: "Syrian refugees in Jordan host communities"
co_authors: 'Sam Leone, [Edward Miguel](http://emiguel.econ.berkeley.edu/), [Bailey Palmer](https://baileypalmer.github.io/), [Sandra Rozo](https://www.sandrarozo.net/), [Emma Smith](https://sites.harvard.edu/emmasmith/), and [Sarah Stillman](https://cega.berkeley.edu/person/sarah-stillman/)'
---
[[paper](https://www.nber.org/papers/w33408?utm_campaign=ntwh)], [[pre-analysis plan](https://www.socialscienceregistry.org/trials/6141)], [[coverage by VoxDev](https://voxdev.org/topic/migration-urbanisation/refugee-housing-policy-learning-housing-subsidies-syrian-refugees)]




## Abstract

This study experimentally evaluates a housing assistance program for Syrian refugees in Jordan, examining impacts on both refugee recipients and their Jordanian neighbors. Through a randomized controlled trial design, we find that full rental subsidies and housing improvements improved short-run housing quality and reduced expenditures, but did not yield sustained economic benefits. Unexpectedly, the program led to deterioration in child socio-emotional well-being and strained relations between Jordanian neighbors and refugees. These findings highlight critical trade-offs in refugee assistance programs and the fragility of social cohesion in host communities.

## Key Findings

The program generated limited positive impacts on refugee well-being while creating unintended negative consequences:

- **Housing impacts**: Significant reduction in out-of-pocket housing expenditures ($85 per month) with improvements in short-run housing quality
- **Child well-being**: Negative effect on child socio-emotional well-being (0.34 SD decrease), the only impact surviving 1.5 years post-program
- **Social cohesion**: Substantial deterioration in Jordanian neighbors' attitudes toward refugees (0.33 SD decrease in social attitudes index)
- **Economic outcomes**: No significant sustained impacts on household consumption, employment, or adult mental health
- **Mechanisms**: Evidence of aid redistribution, with treatment households receiving less food assistance and experiencing increased food insecurity during program implementation


![Treatment Effect on Main Outcomes](/images/publications/subsidies-thumb.png)
*Figure: Treatment effects on primary outcomes with data pooled across all the survey rounds.*

## Methodology

We employ a cluster-randomized design with instrumental variables estimation to assess program impacts:

$$
y_{ict} = \beta_0 + \beta_1\hat{T}_{ic} + X'_c\Lambda + W'_{ic}\Gamma + \mu_{ict} + \epsilon_{ict}
$$

where $y_{ict}$ represents outcomes for household $i$ in community $c$ at time $t$, $\hat{T}_{ic}$ is predicted treatment status from the first-stage regression, $X_c$ includes community stratification variables, and $W_{ic}$ captures baseline household covariates. Standard errors are clustered at the community level (the unit of randomization).

## Data and Experimental Design

- **Duration:** 3.5 years of follow-up (midline during program, endline immediately after, follow-up 1.5 years post-program)
- **Treatment:** Full rental subsidies (9-18 months) plus housing improvements, averaging $2,200 per household—roughly 54% of annual per capita income
- **Innovation:** Representative sample of host community neighbors to measure spillover effects on social attitudes, policy preferences, and altruism
- **Pre-registration:** AEA RCT Registry #AEARCTR-0006141

## Policy Implications

Our findings reveal important tensions in refugee assistance programs. While housing subsidies achieved proximate goals of improving shelter quality and reducing rental burden, they failed to generate sustained improvements in living standards. 

These results suggest that assistance delivery mechanisms matter: 70% of refugee respondents stated they would have preferred direct cash transfers, which may be less observable to neighbors and generate less resentment. The findings also highlight the risk of aid redistribution—both formal (reduced food assistance) and informal (household recomposition)—which can dilute program benefits.
