---
title: "Relaxing Credit and Information Constraints: Five-Year Experimental Evidence from Tanzanian Agriculture"
collection: publications
permalink: /publication/SoilDoc1
date: 2025-01-01
status: 'published'
venue: 'Economic Development and Cultural Change'
layout: single
header:
  overlay_image: /images/publications/agriculture-header.jpg
  overlay_filter: 0.3
  caption: "Agricultural productivity research in Tanzania"
co_authors: '[Marshall Burke](http://web.stanford.edu/~mburke/), [Aurélie Harou](https://aurelieharou.com/), [David Lobell](https://profiles.stanford.edu/david-lobell), [Malgosia Madajewicz](https://people.climate.columbia.edu/users/profile/malgosia-madajewicz), [Christopher Magomba](https://basis.ucdavis.edu/people/christopher-magomba), [Hope Michelson](https://www.hopemichelson.org/), [Cheryl Palm](https://abe.ufl.edu/people/faculty/cheryl-palm/), and [Jiani Xue](https://marketing.wharton.upenn.edu/profile/jennyxue/)'
---

[[published paper](https://www.journals.uchicago.edu/doi/10.1086/731589)], [[coverage by MRR Innovation Lab](https://basis.ucdavis.edu/news/qa-hope-michelson)], [[data and code](https://dataverse.harvard.edu/dataset.xhtml?persistentId=doi:10.7910/DVN/FVLQF5)]

## Abstract

This paper examines the long-term impacts of relaxing credit and information constraints on smallholder agricultural productivity in Tanzania. We conduct a five-year randomized controlled trial providing farmers with access to agricultural credit and personalized soil fertility information. Our results reveal substantial heterogeneity in treatment effects, with larger productivity gains concentrated among higher-productivity farmers.

## Key Findings

![Agricultural Productivity Results](/images/publications/agriculture-thumb.png)
*Figure: Heterogeneous treatment effects on agricultural productivity across the distribution. Panel (a) shows self-reported productivity, while Panel (b) presents GPS-corrected measurements.*

## Methodology

We estimate unconditional quantile treatment effects using the re-centered influence function following Firpo et al. (2009):

$$
RIF(Y; q_\tau, F_Y)=q_\tau +IF(Y;q_\tau)=q_\tau + \frac{\tau-\mathbb{1}\{Y\leq q_\tau\}}{f_Y(q_\tau)}
$$

where $IF(Y;q_\tau)$ is the influence function of the quantile $q_\tau$, $\mathbb{1}\{Y\leq q_\tau\}$ is an indicator that equals unity if productivity is less than or equal to $q_\tau$ and zero otherwise, and $f_Y(q_\tau)$ is the density of the unconditional distribution of productivity evaluated at $q_\tau$. We then regress the RIF on treatment indicators using OLS.

This approach allows us to estimate treatment effects at different points of the unconditional productivity distribution, revealing important heterogeneity that would be masked by standard mean-effects estimators.

## Data and Experimental Design

- **Sample:** 1,050 smallholder farmers across three districts in Tanzania
- **Duration:** Five years
- **Treatment arms:** 
  - Credit access only
  - Soil testing information only
  - Combined credit + information
  - Pure control
- **Primary outcome:** Agricultural productivity, measured via farmer self-reports and GPS-verified plot measurements
- **Secondary outcomes:** Input use, crop choice, investment decisions

## Policy Implications

Our findings suggest that information interventions are most effective when targeted to higher-productivity farmers who have the capacity to act on recommendations. Overall, bundling credit access with information generates the largest gains. This has important implications for the design of agricultural credit programs in developing countries.
