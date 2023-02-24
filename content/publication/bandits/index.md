---
title: "Tight Regret and Complexity Bounds for Thompson Sampling via Langevin Monte Carlo"

weight: 25

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- Tom Huix
- admin
- Alain Durmus

# Author notes (optional)
# author_notes:
# - "Equal contribution"
# - "Equal contribution"
date: "2023-01-30T00:00:00Z"
doi: ""

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: Artificial Intelligence and Statistics, 2023
publication_short: AISTATS, 2023

abstract: 'In this paper, we consider high dimensional contextual bandit problems. Within this setting, Thompson Sampling and its variants have been proposed and successfully applied to multiple machine learning problems. Existing theory on Thompson Sampling shows that it has suboptimal dimension dependency in contrast to upper confidence bound (UCB) algorithms. To
circumvent this issue and obtain optimal regret bounds, (Zhang 2021) recently proposed to mod-
ify Thompson Sampling by enforcing more exploration and hence is able to attain optimal regret
bounds. Nonetheless, this analysis does not permit tractable implementation in high dimensions.
The main challenge therein is the simulation of the posterior samples at each step given the available observations. To overcome this, we propose and analyze the use of Markov Chain Monte Carlo methods. As a corollary, we show that for contextual linear bandits, using Langevin Monte Carlo (LMC) or Metropolis Adjusted Langevin Algorithm (MALA), our algorithm attains optimal regret bounds. We also obtain a bound on the number of data evaluations for LMC and MALA. Finally, we validate our findings through numerical simulations and show that we outperform vanilla Thompson sampling in high dimensions.'

# Summary. An optional shortened abstract.
summary: 'We propose and analyze the use of Markov Chain Monte Carlo methods as an implementation of Thompson sampling. Our algorithm attains optimal regret bounds, while also providing explicit bounds on the number of data evaluations for LMC and MALA. Finally, we validate our findings through numerical simulations and show that we outperform vanilla Thompson sampling in high dimensions.'

tags: []

# Display this page in the Featured widget?
featured: true

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  focal_point: "Center"
  preview_only: true

---
