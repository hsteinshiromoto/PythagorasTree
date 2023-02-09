---
alias: 
tags: definition, linear algebra
date created: Monday, 18th January 2021, 4:09:06 pm
date modified: Monday, 30th January 2023, 9:11:20 pm
---

# Directional Derivative

## Definition

**Definition**. Let $f\in\mathcal{C}^\infty(\mathbb{R}^n)$, and $c:[0,1]\to\mathbb{R}^n$ a curve passing through a point $p=(p^1,\ldots,p^n)$ with direction $v=[v^1,\ldots,v^n]$  is given. The _directional derivative_ of $f$ in the direction of $v$ at $p$ is defined as
$$D_vf=\dfrac{f(c(t))-f(p)}{t}=\left.\dfrac{d}{dt}\right|_{t=0}f(c(t))=\sum_{i=1}^n\dfrac{dc^i}{dt}(0)\dfrac{\partial f}{\partial x^i}(p)=\sum_{i=1}^nv^i\dfrac{\partial f}{\partial x^i}(p)\;.$$

## References

[[L. W. Tu - An Introduction to Manifolds|Tu11, pp. 11]]