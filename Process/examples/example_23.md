{[[D. Bachman - A geometric approach to differential forms]] pp. 56} Suppose $\phi(a,b,c)=(a+b,a+c,bc,a^2)$, where $0\leq a,b,c\leq1$. Let $M$ the image of $\phi$ with the induced orientation. Suppose $\omega=dy\wedge dz\wedge dw-dx\wedge dz\wedge dw -2y\;dx\wedge dy\wedge dz$. Then,
$$\begin{eqnarray}
\int_M\omega&=\int_R\omega_{\phi(a,b,c)}\left(\dfrac{\partial\phi}{\partial a}(a,b,c),\dfrac{\partial\phi}{\partial b}(a,b,c),\dfrac{\partial\phi}{\partial c}(a,b,c)\right)\;da\wedge db\wedge dc\\
&=\int_R\omega_{\phi(a,b,c)}\left(\begin{bmatrix}1\\1\\0\\2a\end{bmatrix},\begin{bmatrix}1\\0\\c\\0\end{bmatrix},\begin{bmatrix}0\\1\\b\\0\end{bmatrix}\right)\;da\wedge db\wedge dc\\
&=\int_R\begin{vmatrix}1&0&1\\ 0&c&b\\2a&0&0\end{vmatrix}-\begin{vmatrix}1&1&0\\ 0&c&b\\2a&0&0\end{vmatrix}-2(a+c)\begin{vmatrix}1&1&0\\ 1&0&1\\0&c&b\end{vmatrix}\;da\wedge db\wedge dc\\
&=\int_0^1\int_0^1\int_0^12bc+2c^2\;dadbdc=\dfrac{7}{6}
\end{eqnarray}$$