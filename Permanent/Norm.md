---
alias: normed, normed space
tags: linear algebra
category: definition
date created: Wednesday, 8th February 2023, 9:56:47 pm
date modified: Thursday, 9th February 2023, 4:02:02 pm
---

# Norm

## Definition

**Definition**. Let $X$ be a [[vector space]] over the complex number $\mathbb{C}$, a _norm_ on $X$ is a function   $||\cdot||:X\to\mathbb{R}_{\geq0}$ with the following properties:
1.  [Subadditivity](https://en.wikipedia.org/wiki/Subadditive_function "Subadditive function")/[Triangle inequality](https://en.wikipedia.org/wiki/Triangle_inequality "Triangle inequality"): for every $x,y\in X$, the inequality $$||x+y||\leq||x||+||y||$$ holds.
2. [Absolute homogeneity](https://en.wikipedia.org/wiki/Homogeneous_function "Homogeneous function"): for every $x\in X$ and $s\in \mathbb{C}$, $||sx||=|s|\;||x||$, where $|s|$ is the absolute value of $s$.
3. [Positive definiteness](https://en.wikipedia.org/wiki/Positive_definiteness "Positive definiteness"): for every $x\in X$, $||x||=0$ implies $x=0$.
4. Non-negativity: for every $x\in X$, $||x||\geq0$.
A vector space equipped with a norm is said to be a _normed space_.

## References

https://en.wikipedia.org/wiki/Norm_(mathematics)