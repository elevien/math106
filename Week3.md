---
title: Week 3
layout: page
permalink: /Week3/
bibliography:
- refs.bib
---

## Probability theory revisited (1.2)

This is where things get a bit more mathy. To give a proper presentation of stochastic processes on uncountable state spaces, we need to revisit some basic ideas in probability theory and give them a measure theoretic foundation. While is possible to understand a lot about stochastic processes without measure theory, I feel it's important to be familiar with the ideas because it makes a lot of literature that would otherwise be impenetrable accessible. At the level of this course you can mostly think of it as a new language to talk about things we understand intuitively, we are not going to be doing technical measure theory proofs. 

- D 1.2 Note that if we are in a finite state space this is just new terminology to talk about outcomes and events. 
- Also take a look at Appendix C, but you won't need to know this for exams

### Exercises 

- 1.11
- 1.12
- 1.13


## General stochastic processes and filtrations (5.1,5.2)

The goal here is to understand mathematicians think about stochastic processes in general as mathematical objects.  We discuss the general case this week before considering two important examples: Markov Process (generalizing Markov chains) and Gaussian processes (generalizing multivariate Gaussian distributions). 

- D 1.3 (filtration)
- D 5.4 
- P 5.5 (Result about stopping times -- see exercise 5.2)


## Gaussian processes (5.4)

Gaussian process are the only example of a non-Markovian process we will spend significant time on. They are very important for machine learning and if time permits we will discuss some applications. Also, a number of SDEs we will consider are also Gaussian processes and it is helpful to have the two views.  
I will define non-negative operators since they don't define this in class and also convergence in $L_{t}^{\infty}L_{\omega}^2$. Focus on 5.12 and 5.13.

- D 5.6 (Gaussian process)
- T 5.10 You can safely skip this, the important takeaway is that we can associated the kernel with a linear operator on square-integrable functions, and this is a ``nice'' operator
- T 5.11 (I won't prove)
- T 5.12 (Mercer's Theorem) I will prove only if we have time. 
- T 5.13 (KL Theorem) I will sketch the proof. 

### Exercises

- 5.1
- 5.2 (prove for discrete time)
- 5.4 
- Write code to generate samples of a mean zero Gaussian process with given covariance function at times $t_1,\dots,t_n$. Experiment with different paramaters in the Matern kernel family [Matérn covariance function](https://en.wikipedia.org/wiki/Mat%C3%A9rn_covariance_function). 
- Let $X_t$ be stationary OU with correlation
  $$K(s,t) = \frac{\sigma^2}{2\theta} e^{-\theta |t-s|}, \qquad t,s\in [-L,L]. \tag{5}$$
  Show that the eigenfunctions satisfy a boundary value problem of the form
  $$\lambda \phi''(t) = \theta^2 \lambda \phi(t) - \sigma^2 \phi(t), \tag{6}$$
  with appropriate boundary conditions. 