---
title: "Convergence of Langevin Monte Carlo in Chi-Squared and Renyi Divergence"

weight: 25

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- Murat A. Erdogdu,
- Rasa Hosseinzadeh
- admin

date: "2021-07-08T00:00:00Z"
doi: ""

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "Artificial Intelligence and Statistics, 2022"
publication_short: "AISTATS 2022"

abstract: 'We study sampling from a target distribution ν=exp(−f) using the unadjusted Langevin Monte Carlo (LMC) algorithm when the potential f satisfies a strong dissipativity condition and it is first-order smooth with a Lipschitz gradient. We prove that, initialized with a Gaussian random vector that has sufficiently small variance, iterating the LMC algorithm for O(λ2dϵ^(−1)) steps is sufficient to reach ϵ-neighborhood of the target in both Chi-squared and Renyi divergence, where λ is the logarithmic Sobolev constant of ν. Our results do not require warm-start to deal with the exponential dimension dependency in Chi-squared divergence at initialization. In particular, for strongly convex and first-order smooth potentials, we show that the LMC algorithm achieves the rate estimate O(dϵ^{−1}) which improves the previously known rates in both of these metrics, under the same assumptions. Translating this rate to other metrics, our results also recover the state-of-the-art rate estimates in KL divergence, total variation and 2-Wasserstein distance in the same setup. Finally, as we rely on the logarithmic Sobolev inequality, our framework covers a range of non-convex potentials that are first-order smooth and exhibit strong convexity outside of a compact region.'

# Summary. An optional shortened abstract.
summary: We analyze the Langevin Monte Carlo algorithm in the strong divergence measures of Renyi and Chi-Square, and obtain improved rates under the log-Sobolev inequality. In contrast to prior work, our assumptions permit some non-convex potentials, such as those that are strongly convex outside a compact set. 

tags: []

# Display this page in the Featured widget?
featured: true

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  focal_point: "Center"
  preview_only: true

---

