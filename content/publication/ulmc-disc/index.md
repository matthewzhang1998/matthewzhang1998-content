---
title: "Improved Discretization Analysis for Underdamped Langevin Monte Carlo"

weight: 25

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- admin
- Sinho Chewi
- Mufan Bill Li
- Krishnakumar Balasubramanian
- Murat A. Erdogdu

# Author notes (optional)
# author_notes:
# - "Equal contribution"
# - "Equal contribution"
date: "2023-02-16T00:00:00Z"
doi: ""

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["3"]

# Publication name and optional abbreviated publication name.
publication: ""
publication_short: ""

abstract: "Underdamped Langevin Monte Carlo (ULMC) is an algorithm used to sample from unnormalized densities by leveraging the momentum of a particle moving in a potential well. We provide a novel analysis of ULMC, motivated by two central questions: (1) Can we obtain improved sampling guarantees beyond strong log-concavity? (2) Can we achieve acceleration for sampling? For (1), prior results for ULMC only hold under a log-Sobolev inequality together with a restrictive Hessian smoothness condition. Here, we relax these assumptions by removing the Hessian smoothness condition and by considering distributions satisfying a Poincaré inequality. Our analysis achieves the state of art dimension dependence, and is also flexible enough to handle weakly smooth potentials. As a byproduct, we also obtain the first KL divergence guarantees for ULMC without Hessian smoothness under strong log-concavity, which is based on a new result on the log-Sobolev constant along the underdamped Langevin diffusion. For (2), the recent breakthrough of Cao, Lu, and Wang (2020) established the first accelerated result for sampling in continuous time via PDE methods. Our discretization analysis translates their result into an algorithmic guarantee, which indeed enjoys better condition number dependence than prior works on ULMC, although we leave open the question of full acceleration in discrete time. Both (1) and (2) necessitate Renyi discretization bounds, which are more challenging than the typically used Wasserstein coupling arguments. We address this using a flexible discretization analysis based on Girsanov's theorem that easily extends to more general settings."

# Summary. An optional shortened abstract.
summary: 'Underdamped Langevin Monte Carlo (ULMC) is an algorithm used to sample from unnormalized densities by leveraging the momentum of a particle moving in a potential well. Our analysis achieves the state of art dimension dependence, and is also flexible enough to handle weakly smooth potentials. It also enjoys better condition number dependence than prior works on ULMC.'

tags: []

# Display this page in the Featured widget?
featured: true

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  focal_point: "Center"
  preview_only: true

---
