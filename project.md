---
title: Project guidelines
layout: page
bibliography:
- refs.bib
---


## Overview and format

The final project should take the form of a **research-style document**, comparable in scope and structure to a **research proposal** or the **first 3–4 pages of a paper**. The emphasis is on clarity of ideas, intellectual ambition, and correct use of mathematical and probabilistic tools rather than on producing polished or complete results.

The document must be **typed in LaTeX** and should be written in a professional, academic style.

The project topic must involve **substantial use of probability theory and stochastic processes**. It does *not* need to be limited to material covered explicitly in the course. Almost any problem in modern data science, statistics, or machine learning can be framed naturally in terms of stochastic processes, and you are encouraged to explore these connections.

## Required components and grading breakdown

Your project will be evaluated according to the following components:

### 1. One-paragraph summary (10%)

Begin with a concise paragraph (approximately 5–8 sentences) that clearly states:
- The problem or question you are studying  
- Why it is interesting or important  
- The stochastic-process perspective you will take  
- The main tools or ideas you plan to use  

This paragraph should be understandable to a mathematically trained reader who is not an expert in your specific topic.

### 2. Literature review (40%)

This should be the most substantial section of the project. The goal is to demonstrate that you understand:
- The **existing work** related to your problem  
- How your project fits into or extends that work  
- What mathematical or conceptual gaps remain  

Guidelines:
- Cite primary sources (papers, monographs, review articles) using proper bibliographic references.
- Summarize key models, assumptions, and results, not just high-level claims.
- When relevant, explicitly identify the underlying stochastic processes (e.g., Markov chains, SDEs, point processes, interacting particle systems).
- It is acceptable—and often useful—to discuss multiple communities’ perspectives (e.g., probability, statistics, machine learning, statistical physics).

This section should read like the introduction or background section of a research paper, not a textbook summary.

### 3. Proposed research direction (40%)

This section should clearly articulate what *you* propose to do. Depending on the project, this may include:
- A precise mathematical formulation of a model or problem  
- A proposed analytical approach (e.g., scaling limits, perturbation methods, large deviations, mean-field limits)  
- A proposed computational or simulation-based approach  
- A discussion of expected challenges or limitations  

You should:
- Clearly state assumptions and modeling choices  
- Explain why stochastic-process tools are essential for your approach  
- Describe what kinds of results you expect to obtain (even if you do not yet have them)

This section should be written as if you are proposing a research project to a knowledgeable audience.

### 4. Preliminary results (10%)

Include either:
- Preliminary analytical calculations  
- Small simulation studies  
- Toy models or simplified versions of the main problem  
- Partial results or sanity checks  

These results do not need to be complete or polished. The goal is to demonstrate that you have begun engaging actively with the problem rather than stopping at a purely conceptual level.

Figures or short code snippets may be included if helpful, but they should support—not replace—mathematical reasoning.

## Topic suggestions

Many of you may already have projects in in mind related to existing research you are doing. If you need help coming up with an idea, please reach out. In addition, throughout the course I will try to point to extensions of what we are covering in class which could lead to a project. These will be recorded below. 

- **Generalizations of the Kelly criterion**  
  - Correlated betting opportunities  
  - Sequential or adaptive Kelly strategies  
  - Bayesian formulations where the underlying process is learned online  

