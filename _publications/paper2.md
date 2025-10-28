---
title: "Relaxing Credit and Information Constraints: Five-Year Experimental Evidence from Tanzanian Agriculture"
collection: publications
permalink: /publication/SoilDoc1
date: 2025-01-01
status: 'published'
venue: 'Economic Development and Cultural Change'
layout: single
co_authors: '[Marshall Burke](http://web.stanford.edu/~mburke/), [Aurélie Harou](https://aurelieharou.com/), [David Lobell](https://profiles.stanford.edu/david-lobell), [Malgosia Madajewicz](https://people.climate.columbia.edu/users/profile/malgosia-madajewicz), [Christopher Magomba](https://basis.ucdavis.edu/people/christopher-magomba), [Hope Michelson](https://www.hopemichelson.org/), [Cheryl Palm](https://abe.ufl.edu/people/faculty/cheryl-palm/), and [Jiani Xue](https://marketing.wharton.upenn.edu/profile/jennyxue/)'
---
[[published paper](https://www.journals.uchicago.edu/doi/10.1086/731589)], [[coverage by MRR Innovation Lab](https://basis.ucdavis.edu/news/qa-hope-michelson)], [[data and code](https://dataverse.harvard.edu/dataset.xhtml?persistentId=doi:10.7910/DVN/FVLQF5)]


---
title: "Relaxing Credit and Information Constraints: Five-Year Experimental Evidence from Tanzanian Agriculture"
collection: publications
permalink: /publication/SoilDoc1
date: 2025-01-01
status: 'published'
venue: 'Economic Development and Cultural Change'
co_authors: '[Aurélie Harou](https://aurelieharou.com/), [Marshall Burke](http://web.stanford.edu/~mburke/)...'
---

[[published paper](https://www.journals.uchicago.edu/doi/10.1086/731589)], [[coverage by MRR Innovation Lab](https://basis.ucdavis.edu/news/qa-hope-michelson)], [[data and code](https://dataverse.harvard.edu/dataset.xhtml?persistentId=doi:10.7910/DVN/FVLQF5)]

## Key Findings

![Agricultural Productivity Results](/images/publications/agriculture-thumb.png)

We estimate unconditional quantile treatment effects using the re-centered influence function following Firpo et al. (2009):

$$
RIF(Y; q_\tau, F_Y)=q_\tau +IF(Y;q_\tau)=q_\tau + \frac{\tau-\mathbb{1}\{Y\leq q_\tau\}}{f_Y(q_\tau)}
$$

where $IF(Y;q_\tau)$ is the influence function of the quantile $q_\tau$, $\mathbb{1}\{Y\leq q_\tau\}$ is an indicator that equals unity if productivity is less than or equal to $q_\tau$ and zero otherwise, and $f_Y(q_\tau)$ is the density of the unconditional distribution of productivity evaluated at $q_\tau$. We then regress the RIF on treatment indicators using OLS.
