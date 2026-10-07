---
layout: about
title: about
permalink: /
subtitle:
profile:
  align: right
  image: headshot.jpg
  image_circular: false  # crops the image to make it circular
  more_info:
news: false  # includes a list of news items
selected_papers: false  # includes a list of papers marked as "selected={true}"
social: false  # includes social icons at the bottom of the page
---

I'm a postdoc working at Los Alamos National Laboratory in the Computational Physics and Methods group (CAI-2) and the [Center for Nonlinear Studies](https://cnls.lanl.gov/External) (CNLS).
I graduated with a PhD in Mathematics from Oregon State University, supervised by Robert Higdon.

[My PhD dissertation](https://ir.library.oregonstate.edu/concern/graduate_thesis_or_dissertations/rr172599c) focuses on developing computationally efficient time-stepping methods for the shallow water equations, with the long term goal of speeding up realistic simulations of the ocean and atmosphere at the climate scale.
By combining a CFL optimized method, a certain operator splitting, and local time-stepping, we achieved a speedup of more than 10x in the US Department of Energy's ocean model, MPAS-Ocean.

As a postdoc at LANL, I've worked on tensor train methods for geophysical fluids, the open-source phase field model for advanced manufacturing [Tusas](https://github.com/chrisknewman/tusas), and written a Python package for building [tensor trains from sparse tensors](https://gitlab.com/jamie-lilly/sparsett).

Currently, I'm working on applying ML methods, augmented by process-based parameterizations, to missing-physics problems in the ocean.
We hope to augment existing turbulent vertical mixing parameterizations for temperature and salinity transport in polar ocean regions with models trained on large eddy simulation data..
Since these physics are important to energy transfer between the ocean and atmosphere, they are important to get right for climate scale applications.

In general, I'm interested in numerical methods for solving problems faster -- particularly problems related to our Earth's climate system.

