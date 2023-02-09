---
alias: 
tags: topology
category: definition
date created: Friday, 8th January 2021, 3:33:42 pm
date modified: Friday, 3rd February 2023, 11:29:49 am
---
# Metric

## Definition

**Definition**. Let $X$ be a set, a function $d:X\times X\to\mathbb{R}$ is said to be a _metric_ if
* It is symmetric: for every $x_1,x_2\in X$, the equality $d(x_1,x_2)=d(x_2,x_1)$ holds.
* Indicernible: for every $x_1,x_2\in X$ such that $x_1=x_2$, the equality $d(x_1, x_2)=0$ holds.
* Positive: for every $x_1,x_2\in X$ such that $x_1\neq x_2$, the ineequality $d(x_1, x_2)>0$ holds.
* Subadditive: for every $x_1,x_2,x_3\in X$, the inequality $d(x_1, x_3)\leq d(x_1, x_2) + d(x_2, x_3)$ holds.

## References


