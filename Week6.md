---
title: Week 6
layout: page
permalink: /Week6/
bibliography:
- refs.bib
---


## Itô integral, Itô formula (7.1,7.2)

We covered most of these sections. I didn't prove the  Itô formula. 

## Examples (7.3)

We looked the examples of the OU process and geometric Brownian Motion. 

**Notes**: <a href="{{ '/lecture_notes/week6/2-10-2026_stochastic_integrals.pdf' | relative_url }}">Stochastic intergrals and SDEs</a>


### Exercises
- 7.1
- 7.3
- 7.5
- 7.6
- 7.7
- Let  
  $$
  X_t = e^{-\gamma t}W_{\frac{\sigma^2}{2\gamma}(e^{2\gamma t}-1)},
  $$
  where $W_t$ is a Wiener process.  
  Deduce that it satisfies the Ornstein–Uhlenbeck SDE  
  $$
  dX_t = -\gamma X_t\,dt + \sigma\, dW_t.
  $$

- Define a stochastic integral using Riemann sums with partition $P=\{0=t_0<t_1<\dots<t_n=t\}$ and evaluation point  
  $$
  t_* = \lambda t_{j+1} + (1-\lambda)t_j,\qquad \lambda\in[0,1].
  $$
  Using this definition, derive the formula for  
  $$
  \int_0^t W_s\, dW_s.
  $$
- Consider the Gaussian process $$
Q = \int_0^te^{-\gamma(t-s)}dW_s
$$
which appeared in the solution of the OU process.
Derive its covariance function. 


