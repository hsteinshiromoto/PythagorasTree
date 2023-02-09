{[[D. Bachman - A geometric approach to differential forms]]} Let $C$ be the curve in $\mathbb{R}^2$ parametrized by $\phi(t)=(t^2, t^3)$, where $0\leq t\leq 2$. Let $\nu$ be the [[1-form]] $y\;dx+x\;dy$. We want to calculate $\int_C\nu$.

First, calculate
$$\dfrac{d\phi}{dt}=\langle 2t, 3t^2\rangle\;.$$

So, $dx=2t$ and $dy=3t^2$. From the parametrization, we also know $x=t^2$ and $y=t^3$. Hence, since $\nu=y\;dx+x\;dy$, we have

$$\nu_{\phi(t)}\left(\dfrac{d\phi}{dt}\right)=(t^3)(2t)+(t^2)(3t^2)=5t^4\;.$$

Finally, we integrate
$$\int_C\nu=\int_0^2\nu_{\phi(t)}\dfrac{d\phi}{dt}\;dt=\int_0^25t^4\;dt=32$$