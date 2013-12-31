---
title: Structural Equations
author: Boris Sobolev
abstract: 
categories:
tags:
published: false
---

Structural equations model relationships between connected nodes in the directed acyclic graph as functions of one variable onto another.

### Graphical causal models 

Recent advances in the area of causal inference have been prompted by an understanding the connection between the directed acyclic graph and the factorization of a joint probability function. A directed acyclic graph depicts the causal structure of multivariate data. In such graphs, nodes represent variables and arrows show direct effects between the variables that they connect. An arrow drawn from variable $X$ to variable $Y$ shows a direct effect of $X$ on $Y$, and no effect of $Y$ on $X$. In graph theory, $X$ is said to be a parent of $Y$.

The causal structure of directed acyclic graphs can be linked to the observational data by the Markov assumption. This assumption states that, conditional on its parents, a variable is independent of any other variable in the graph. Therefore, the dependencies among connected nodes in the graph define the set of the conditional probabilities of variables on their parents. The product of these conditional probabilities is said to be the factorization of the joint probability function of the variables.

### Functional causal models

To express the directionality of dependency, the equation is interpreted with a causal graph, in which arrows are drawn from causes to their effects, and more importantly, the absence of an arrow makes the empirical claim that Nature assigns values to one variable irrespective of another. A direct acyclic graph shows the presence of direct influence of $X$ on $Y$, and the absence of influence of $Y$ on $X$.

The structural equations specify the mechanism of influences by deterministic functional equations, and probabilities are introduced through unobserved random variables in these equations.

<div>\[ x_i=f_i(pa_i,u_i), \; i = 1,\ldots,n \]</div>

Each equation represents an autonomous dependency of $x_i$ on parents $pa_i$, and $u_i$ stands for all factors, other than the parents in question, that could possibly affect $x_i$ when $pa_i$ is held constant. Unlike a system of algebraic equations, structural equations represent assignment of values to $x_i$ given values of $pa_i$ and $u_i$.

### Structural equations in causal reasoning

Pearl proposed that structural equations be used for answering causal queries arising from directed acyclic graphs.27 He noted that structural equations present formulas for computing potential outcomes under various policies.24 To evaluate a potential value of the outcome, the equation for the variable representing a policy is replaced with its counterfactual value, and the values for the outcome variables are then computed, keeping all other equations unchanged.

This technique of replacing an equation for the causal variable with a fixed value captures the notion of controlled experiments because each structural equation corresponds to a mechanism linking multiple causes to studied effects. Pearl has shown that a structural equation model enables estimation of the causal effect of one variable on another, on the basis of knowledge of the conditional probabilities derived from observational studies.