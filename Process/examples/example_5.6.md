[[D. Bachman - A geometric approach to differential forms]] Example 5.6: Suppose $\omega=f(x,y,z)\;dx\wedge dy+g(x.y.z)\;dy\wedge dz+h(x,y,z)\;dx\wedge dz$ Find $d\omega$.  Repeath the above with $f(x,y,z)=x^2y$, $g(x,z,y)=y^2z$ and 
$$\begin{eqnarray}
\omega([1,0,0],[0,1,0],[0,0,1])&=&f(x,y,z)\begin{vmatrix}1&0&0\\ 0&1&0\end{vmatrix}+g(x,y,z)\begin{vmatrix}0&1&0\\ 0&0&1\end{vmatrix}+h(x,y,z)\begin{vmatrix}1&0&0\\ 0&0&1\end{vmatrix}\\
&=&f(x,y,z)-g(x,y,z)+h(x,y,z)
\end{eqnarray}$$

$$\begin{eqnarray}
	d\omega([1,0,0],[0,1,0],[0,0,1])&=&\begin{bmatrix}\dfrac{\partial f}{\partial x}\\\dfrac{\partial g}{\partial x}\\\dfrac{\partial h}{\partial x}\end{bmatrix}[1, 0 ,0]
	-\begin{bmatrix}\dfrac{\partial f}{\partial y}\\\dfrac{\partial g}{\partial y}\\\dfrac{\partial h}{\partial y}\end{bmatrix}[0, 1 ,0]
	+\begin{bmatrix}\dfrac{\partial f}{\partial z}\\\dfrac{\partial g}{\partial z}\\\dfrac{\partial h}{\partial z}\end{bmatrix}[0, 0, 1]\\
	&=&\dfrac{\partial f}{\partial x}-\dfrac{\partial g}{\partial y}+\dfrac{\partial h}{\partial z}\\
	&=&2xy-2yz
\end{eqnarray}$$