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



## General stochastic processes and filtrations (5.1,5.2)

For details see <a href="{{ '/lecture_notes/week3/1-22-2026_filtration-stopping-times.pdf' | relative_url }}">Filtration and stopping times</a>


## Gaussian processes (5.4)

For details see <a href="{{ '/lecture_notes/week3/1-22-2026_gaussian-processes.pdf' | relative_url }}">Gaussian processes</a>

 


### Exercises


- 1.11
- 1.12
- 1.13
- 5.1
- 5.2 (prove for discrete time)
- 5.4 
- Write code to generate samples of a mean zero Gaussian process with given covariance function at times $t_1,\dots,t_n$. Experiment with different paramaters in the Matern kernel family [Matérn covariance function](https://en.wikipedia.org/wiki/Mat%C3%A9rn_covariance_function). 
- Consider the stationary Ornstein–Uhlenbeck (OU) process restricted to a finite interval $[0,T]$. Its covariance kernel is
$$
K(s,t) = \frac{\sigma^2}{2\theta}\, e^{-\theta \lvert t-s\rvert},
\qquad s,t\in[0,T].
$$ Show that any eigenfunction $\phi$ satisfying (E) also satisfies the second–order ODE
$$
\lambda\,\phi''(t)
= \theta^2\,\lambda\,\phi(t) - \sigma^2\,\phi(t),
\qquad t\in(0,T),
$$
together with boundary conditions at $t=0$ and $t=T$ that can be derived from the
integral representation of $(\mathcal{K}\phi)(t)$ at the endpoints. Hint: Write the operator action explicitly by splitting the integral at $s$:
$$
(\mathcal{K}\phi)(s)
= \int_0^s e^{-\theta(s-t)}\,\phi(t)\,dt
\;+\;
\int_s^T e^{-\theta(t-s)}\,\phi(t)\,dt.
$$
Differentiate with respect to $s$ to obtain first–order
relations, differentiate once more, and use the eigenvalue equation. 

(I recommend focusing on the exam practice problems -- see <a href="{{ '/exams/midterm_practice.pdf' | relative_url }}">midterm practice problems</a>)