---
title: Week 5
layout: page
permalink: /Week5/
bibliography:
- refs.bib
---


## Markov processes (5.3)

We will introduce general Markov processes and derive the forward backward equations in this setting. We have already seen that the OU process (GP with exponential Kernel) is an example of a Gaussian processes which is also Markov process. 

**Notes**: [General Markov processes and semigroup theory](lecture_notes/week5/2-3-2026_markovprocesses.pdf)


## Wiener processes as limit of RW and KL Expansion (6.1,6.3, 6.2)

We will introduce the Wiener process as the scaling limit of a Random walk. We will show this is the Gaussian process with min kernel we encountered before and we will compute the KL expansion. 
You can skip T6.4 (arcsin law). 


### Exercises
- Show that the operator

  $$
  {\mathcal A}f(x) = f'(x)
  $$

  is unbounded on both $L^\infty(\mathbb{R})$ and $C_0(\mathbb{R})$.

- Consider the ODE

  $$
  \frac{dX_t}{dt} = b(X_t),
  $$

  where $X_t \in \mathbb{R}^n$ and $b:\mathbb{R}^n \to \mathbb{R}^n$ is a smooth vector field.
  When viewed as a (deterministic) stochastic process, show that the generator is

  $$
  {\mathcal A}f(x) = b(x)^\top \nabla f(x).
  $$

- Compute the **adjoint operator** $\mathcal A^*$ corresponding to

  $$
  {\mathcal A}f(x) = b(x)^\top \nabla f(x).
  $$

- Let $X_t$ be a $Q$-process on the finite state space $\{1,\dots,I\}$, and let

  $$
  \frac{dY_t}{dt} = b_{X_t}(Y_t),
  $$

  where each $b_i:\mathbb{R}^n \to \mathbb{R}^n$ is a smooth vector field.
  Show that the process $(X_t,Y_t)$ is a Markov process and derive its generator.
  This type of process is sometimes called a **stochastic hybrid system (SHS)** and
  arises in models of deterministic dynamics evolving in stochastic environments,
  such as ecosystems with randomly switching resource dynamics.
- Solve the Sturm-Liouville problem (6.11) to derive the eigenfunctions in the KL expansion of a Wiener process. 
- 6.1
- 6.9
