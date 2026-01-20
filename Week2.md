---
title: Week 2
layout: page
permalink: /Week2/
bibliography:
- refs.bib
---

## Poisson process (3.4)

Poisson processes are the warm-up for continuous time Markov chains (CTMC) (with finite state spaces), which they call $Q$-processes, although they are not on finite state spaces. 

- D 3.13 (definition of Poisson process). As we discussed in class, the conditions are redundant. Try to come up with a minimal definition that you like (there are different ones)
- T 3.14 (derivation of Poisson distribution). We didn't prove this, but definitely go through it on your own. It's good practice with basic differential equations techniques. 
  

## Continuous time Markov chains/Q-processes (3.5)

Here is where we start to connect stochastic processes to differential equations. If needed, you should review basic ideas of linear differential equations, like matrix exponential and linear stability theory. Understanding the definition of the CTMC and derivation of the forward backward equations is important.

## Embedded Chains, Gillespie algorith, and Ergodic Theorem (3.6,3.7)

- T3.15 (embedded chain) I will give a derivation, if not a proof, of this. 
- T3.16 
- T3.17 (convergence). 
- T3.18 (ergodic theorem)

Two things I will spend a bit more time talking about are: 
- Time-change representations. They discuss this at the end of the book in Section 13.3 in the context of chemical reaction networks, but I find it helpful to better understand CTMC. 
- Gillespie algorithm. This is how we simulate CTMC. They also discuss this in more detail in Chapter 13, but the construction of the embedded chain is essentially a proof that the Gillespie algorithm works. 
You don't need to read Chapter 13 as I will provide a self contained introduction to these topics in the context of general CTMC. 

## Time reversal and detailed balance (3.8)

Time reversal is an important idea both in physics (relating to out of equilibrium systems and entropy production) and in machine learning (in the context of diffusion models). They talk about detailed balance in the book, but I will introduce an additional concept: Entropy production rate. This is how we quantify how far out of equilibrium a system is. 



## Hidden Markov models (3.10)

We don't cover this, but it's very useful to review particularly for your projects. 

### Exercises 

- 3.7
- 3.8 This is the very important Kolmogorov backward equation, but there is a typo: $P$ should be $Q$. 
- 3.11
- 3.12 This gets at an important connections between Poisson point processes and partitions which is important in disordered systems. 
- 3.13
- 3.16 The connection between Boundary value problems and first passage times will come back later. 
- Added 1/13: We've seen how the Perron Frobenius theorem applies to the matrix $P$. Now explain how it applies to $Q$. In particular, what does it say about the spectrum. 
- Added 1/13: If $N_t$ is a Poisson process with rate $=1$ and $\gamma> 0$, then what is $\tilde{N}_t = N_{\gamma t}$. 
