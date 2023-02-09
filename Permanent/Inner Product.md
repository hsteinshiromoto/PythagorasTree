---
alias: inner product space
tags: linear algebra
category: definition
date created: Thursday, 9th February 2023, 11:48:07 am
date modified: Thursday, 9th February 2023, 4:02:28 pm
---

# Inner Product

## Definition

**Definition**. An _inner product space_ is a [[vector space]] $V$ over the field $F$ together with an _inner product_, that is a map $\langle \cdot ,\cdot \rangle :V\times V\to F$ that satisfies the following three properties for all vectors $x,y,z\in V$ and all scalars $a,b\in F$
-   _Conjugate symmetry_: $\langle x,y\rangle ={\overline {\langle y,x\rangle }}$.
	  As $a={\overline {a}}$ if and only if $a\in\mathbb{R}$, conjugate symmetry implies that $\langle x,x\rangle$ is always a real number. If $F=\mathbb {R}$ conjugate symmetry is just symmetry.
-  _Linearity_: $\langle ax+by,z\rangle =a\langle x,z\rangle +b\langle y,z\rangle$.
-  _Positive-definiteness_: if $x\neq0$, then $\langle x,x\rangle >0$. 

The inner product induces a [[norm]]. Thus, an inner product space is also a [[Norm|normed space]].

## References

https://en.wikipedia.org/wiki/Inner_product_space