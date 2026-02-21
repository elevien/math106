---
title: Week 7
layout: page
permalink: /Week7/
bibliography:
- refs.bib
---

## Existence and uniqueness (7.3)

We proved the uniqueness part of the existence and uniqueness theorem.

## Numerical methods (7.5)

We derived the Itô-Taylor expansion and discussed how it gives rise to the Euler and Milstein methods. I mentioned Runge-Kutta methods but did not derive them. We then covered the concepts of strong and weak order.

We did not talk about Stratonovich SDEs, but you should learn about this on your own (see exercises below).

## Fokker-Planck equation (8.1, 8.2)

The Fokker-Planck equation is a linear differential equation describing the evolution of probability distributions, analogous to the linear equation we had for the $Q$-process. In this setting, it is a parabolic equation, and it is often the most useful tool for obtaining concrete results about stochastic differential equations. In the physics literature, this is often the dominant viewpoint on SDEs.

We derived the FP equation for Itô diffusion, and then I showed how, for Brownian dynamics, it can be derived from a gradient flow on densities starting from thermodynamic considerations (free-energy minimization). Along the way, the concept of a probability current was introduced, extending the analogous idea for the Q-process. We then discussed diffusion on a sphere. This equation can also be understood in terms of probability flux (see exercises).

We closed by deriving the time reversal of an SDE. Next week we will connect this to thermodynamics.

### Exercises

- Spend an hour learning about the Stratonovich integral and try to convince yourself:
    - Why it makes sense when thinking of white noise as the zero-correlation limit of an OU process
    - What the generalization of the Itô isometry is
    - Why we recover the usual chain rule
- Show that for diffusion on a sphere, the probability current normal to the sphere vanishes.
- 8.4
- 8.7
- 8.8 (hint: It is Gaussian.)
