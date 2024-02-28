Let $P = (a,0)$ and $Q = (-a,0)$ for some positive number $a$, and consider the curve $C$ of all points $X$ such that $(XP)(XQ) = a^2$; that is, the product of the distances from $X$ to $P$ and to $Q$ is equal to $a^2$.
(a) Sketch $C$.  
(b) Write $C$ as the graph of a polar equation $r = f(\theta)$.  
(c) Suppose instead we had $D$ defined as the set of all points $X$ such that $(XP)(XQ) = 2a^2$. Sketch $D$. What if we used $(XP)(XQ) = \frac12a^2$ instead?

(a)
If we set the point $X$ to $$X = (x_{1}, y_{1}),$$by the distance formula, we get: 
$$\sqrt{(-a-x_{1})^{2}+(0-y_{1})^{2}}\sqrt{(a-x_{1})^{2}+(0-y_{1})^{2}}=a^2$$ which we can simplify.
$$
\begin{align*}
\sqrt{(-a-x_{1})^{2}+(0-y_{1})^{2}}\sqrt{(a-x_{1})^{2}+(0-y_{1})^{2}}&=a^2 \\
\sqrt{(a+x_{1})^{2}+y_{1}^{2}}\sqrt{(a-x_{1})^{2}+y_{1}^{2}}&=a^2 \\
\left( (a+x_{1})^{2}+y_{1}^{2} \right) \left( (a-x_{1})^{2}+y_{1}^{2} \right) &=a^4 \\
-2 a^2 x_1^2 + 2 a^2 y_1^2 + 2 x_1^2 y_1^2 + x_1^4 + y_1^4 = 0
\end{align*}
$$

Graphed this equation looks like an $\infty$ symbol that goes from $-\sqrt{ 2 }$ to $\sqrt{ 2 }$.
![[Screenshot 2024-02-28 at 3.55.49 PM.png]]

(b)
In polar coordinates, this is
$$r=\sqrt{2\cos2\theta}.$$

(c)
If $(XP)(XQ) = 2a^2$, it would look like an elongated oval.
If $(XP)(XQ) = \frac{a^2}{2}$, it would look like two circles surround $P$ and $Q$. 