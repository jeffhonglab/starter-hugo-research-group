---
title: Simulation Optimization
date: 2022-01-31
weight: 1

tags:
 - research topics

---

<!--more-->

<DIV align="justify">
Simulation optimization (SO), almost called optimization via simulation, is one of the most important and fast developing areas in stochastic simulation, because simulation models are often built with the goal of optimization. Generally, SO problems may be formulated as follows:
\[
\min_{\mathbf{x}\in\Theta}\ \mathbf{E}[G(\mathbf{x},\omega)],
\]
where $\mathbf{x}$ denotes the decision variables, $\omega$ denotes the randomness in simulation and the expectation is taken with respect to the distribution of $\omega$. We typically assume that $G(\cdot,\cdot)$ has no closed-form expression, but it is the output of a stochastic simulation model, and it can be observed by running simulation experiments at $\mathbf{x}$. The feasible region $\Theta$ may take different forms, resulting in different types of SO problems, e.g., continuous SO, discrete SO, stochastically constrained SO etc.

My co-authors and I have developed a number of algorithms in this area, including discrete SO algorithms such as COMPASS, AHA and GPS, and continuous SO algorithms such as STRONG. Here is the list of publications and preprints that we have in this area, including a recent review paper on surrogate-based simulation optimization. We are currently working on developing software packages and hope to have them online soon.

Recently, my group’s research interest in SO focuses on developing algorithms that can take advantage of modern computing tools such as parallel computing and tensorization to solve high-dimensional SO problems, and on understanding how dimensionality affects the convergence of SO algorithms.
</DIV>
