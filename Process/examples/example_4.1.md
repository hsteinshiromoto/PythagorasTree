([[D. Bachman - A geometric approach to differential forms]] Example 4.1). Let $\omega$ be the differential $2-$form on $\mathbb{R}^3$ given by
$$\omega=xyz\;dx\wedge dy+x^2z\; dy\wedge dz-y\;dx\wedge dz.$$
Consider the vector fields $v_1=\langle y, z, x^2\rangle_{(x,y,z)}$ and $v_2=\langle xy, xz, y\rangle_{(x,y,z)}$.

1. What vectors $v_1$ and $v_2$ contain at the point $(1,2,3)$?
2. Which $2-$form is $\omega$ on $T_{(1,2,3)}\mathbb{R}^3$?
3. Use your answers to the previous two questions to compute $\omega(v_1,v_2)$ at the point $(1,2,3)$.
4. Compute $\omega(v_1,v_2)$ at the point $(x,y,z)$. Then plug in $x=1, y=2$ and $z=3$ to check your answer agains the previous question.

Answers:
1. $v_1=\langle2,3,1\rangle$ and $v_2=\langle2,3,2\rangle$.
2. $\omega=6\;dx\wedge dy+3\; dy\wedge dz-2\;dx\wedge dz.$
3. $\omega(v_1,v_2)=6\begin{vmatrix}y&xy\\z&xz\end{vmatrix}+3\begin{vmatrix}z&xz\\x^2&y\end{vmatrix}-2\begin{vmatrix}y&xy\\x^2&y\end{vmatrix}$. At $(1,2,3)$, $\omega(v_1,v_2)=5$
4. Same as #3