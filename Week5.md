---
title: Week 5
layout: page
permalink: /Week5/
bibliography:
- refs.bib
---


## Markov processes (5.3)

We will introduce general Markov processes and derive the forward backward equations in this setting. We have already seen that the OU process (GP with exponential Kernel) is an example of a Gaussian process which is also a Markov process. 

**Notes**: <a href="{{ '/lecture_notes/week5/2-3-2026_markovprocesses.pdf' | relative_url }}">General Markov processes and semigroup theory</a>


## Wiener processes as the limit of RW and KL Expansion (6.1,6.3, 6.2)

There are many results in this chapter we won't cover. The things we covered in class are: 
- Derivation of Wiener process as the scaling limit of a symmetric random walk 
- We will discuss but not prove Donsker’s Theorem (T6.4). You should be familiar with the statement and exactly what we mean by convergence in distribution. 
- We derived the kernel and KL expansion of a Wiener process (but we did not cover the Haar basis expansion (T6.5) in this section)
- We did cover Example 6.6 
- We derived the diffusion equation 
- We did not discuss Kolmogorov's continuity theorem (T6.10,T6.12) although we did get a taste of this idea when we looked at smoothness of GP kernels.


### Exercises
- Show that the operator

  $$
  {\mathcal A}f(x) = f'(x)
  $$

  is unbounded on a dense subset $C_0(\mathbb{R})$. In particular, take the domain to be the space $C_c^1(\mathbb{R})$ of continuous and once differentiable functions.

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
