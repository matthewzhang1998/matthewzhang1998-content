---
title: "Convergence and Optimality of Policy Gradient Methods in Weakly Smooth Settings"

weight: 25

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- admin
- Murat Erdogdu
- Animesh Garg

# Author notes (optional)
# author_notes:
# - "Equal contribution"
# - "Equal contribution"
date: "2021-10-30T00:00:00Z"
doi: ""

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: AAAI Conference on Artificial Intelligence
publication_short: AAAI

abstract: 'Policy gradient methods have been frequently applied to problems in control and reinforcement learning with great success, yet existing convergence analysis still relies on non-intuitive, impractical and often opaque conditions. In particular, existing rates are achieved in limited settings, under strict smoothness and bounded conditions. In this work, we establish explicit convergence rates of policy gradient methods without relying on these conditions, instead extending the convergence regime to weakly smooth policy classes with L2 integrable gradient. We provide intuitive examples to illustrate the insight behind these new conditions. We also characterize the sufficiency conditions for the ergodicity of near-linear MDPs, which represent an important class of problems. Notably, our analysis also shows that fast convergence rates are achievable for both the standard policy gradient and the natural policy gradient algorithms under these assumptions. Lastly we provide conditions and analysis for optimality of the converged policies.'

# Summary. An optional shortened abstract.
summary: We analyze the convergence of policy gradient and natural policy gradient when the policy class satisfies weak smoothness guarantees and L2 integrability, under a variety of learning rate decay functions. This is much more general than existing work, where Lipschitz gradients and absolute boundedness are required. We also provide analysis for the optimality of stationary points, and supplement our analysis with empirical verification.

tags: []

# Display this page in the Featured widget?
featured: true

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  focal_point: "Center"
  preview_only: true

---
