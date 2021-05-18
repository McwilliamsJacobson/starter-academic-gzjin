---
title: "Nonlocal stochastic-partial-differential-equation limits of spatially correlated noise-driven spin systems derived to sample a canonical distribution"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- admin
- Jeremy L. Marzuola
- Jonathan C. Mattingly
- Katherine A. Newhall

# Author notes (optional)
author_notes:
- "First Author"

date: "2020-10-12"
doi: "10.1103/PhysRevE.102.052112"

# Schedule page publish date (NOT publication's date).
publishDate: "2020-10-12"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: Physical Review E 
publication_short: Phys. Rev. E 

abstract: For a noisy spin system, we derive a nonlocal stochastic version of the overdamped Landau-Lipshitz equation designed to respect the underlying Hamiltonian structure and sample the canonical or Gibbs distribution while being driven by spatially correlated (colored) noise that regularizes the dynamics, making this Stochastic partial differential equation mathematically well-posed. We begin from a microscopic discrete-time model motivated by the Metropolis-Hastings algorithm for a finite number of spins with periodic boundary conditions whose values are distributed on the unit sphere. We thus propose a future state of the system by adding to each spin colored noise projected onto the sphere, and then accept this proposed state with probability given by the ratio of the canonical distribution at the proposed and current states. For uncorrelated (white) noise this process is guaranteed to sample the canonical distribution. We demonstrate that for colored noise, the method used to project the noise onto the sphere and conserve the magnitude of the spins impacts the equilibrium distribution of the system, as coloring projected noise is not equivalent to projecting colored noise. In a specific scenario we show this break in symmetry vanishes with vanishing proposal size; the resulting continuous-time system of Stochastic differential equations samples the canonical distribution and preserves the magnitude of the spins while being driven by colored noise. Taking the continuum limit of infinitely many spins we arrive at the aforementioned version of the overdamped Landau-Lipshitz equation. Numerical simulations are included to verify convergence properties and demonstrate the dynamics.


# Summary. An optional shortened abstract.
summary: We derive a nonlocal stochastic version of the overdamped Landau-Lipshitz equation designed to respect the underlying Hamiltonian structure and sample the canonical or Gibbs distribution while being driven by spatially correlated (colored) noise that regularizes the dynamics, making this Stochastic partial differential equation mathematically well-posed.

tags: ["Landau-Lifschitz-Gilbert equation", "Langevin equation", "Metropolis algorithm", "Stochastic analysis"]

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: ''
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Image credit: [**Gao 2020**](https://doi.org/10.1103/PhysRevE.102.052112)'
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
- Yuan Gao's 1st Project

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
#slides: example
---

