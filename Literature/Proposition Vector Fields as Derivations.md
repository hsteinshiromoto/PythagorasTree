---
alias: 
tags: linear algebra, result
date created: Friday, 27th January 2023, 2:47:43 pm
date modified: Monday, 30th January 2023, 9:45:32 pm
---
# Vector Fields as Derivations

## Proposition

**Proposition**. Let $X\in\mathcal{C}^\infty$ be a [[vector field]] on an [[Open Set|open]] subset $U\subset\mathbb{R}^n$ and $f\in\mathcal{C}^\infty(U)$ function on $U$.  Define the  function $Xf$ on $U$ given, for every $p\in U$, as $(X f)(p) = X_pf$. In terms of the [[Corollary Tangent Vectors are Derivations|basis of the vector field]], $X_f(p)$ is given by
$$(Xf)(p)=\sum_{i=1}^na^i(p)\dfrac{\partial f}{\partial x_i}(p)\;.$$
By letting, $a\in\mathcal{C}^\infty(U,\mathbb{R})$ be a function, the [[Vector Field]] $X$ gives rise to the [[derivation]]
$$\begin{array}{rcl}
\mathcal{C}^\infty(U)&\to&\mathcal{C}^\infty\\
f&\mapsto&Xf\;.
\end{array}$$

## References

[[L. W. Tu - An Introduction to Manifolds|Tu11, Section 2.5]]