Let $y$ be the function that satisfies $$y' = x + y^2.$$ and $y(0) = 1$. If the Taylor series of $y$ is given by $$y = a_0 + a_1 x + a_2 x^2 + a_3 x^3 + \dotsb,$$ then find $a_0$, $a_1$, $a_2$, and $a_3$.

Obviously, $a_{0}$ equals $1$ because $y(0) = 1.$
$$
\begin{align}
\frac{d}{dx}\left(1 + a_1 x + a_2 x^2 + a_3 x^3\right) = x \cdot \left(1 + a_1 x + a_2 x^2 + a_3 x^3\right)^2
\end{align}
$$
We also know $a_{1} = 1$ because the slope is $1$ at $(0,1)$.

$$
\begin{align}
\frac{d}{dx}\left(1 + x + a_2 x^2 + a_3 x^3\right) &= x + \left(1 + x + a_2 x^2 + a_3 x^3\right)^2 \\
3 a_3 x^2 + 2 a_2 x + 1 &= x + (1 + x + a_2 x^2 + a_3 x^3)^2 \\
\end{align}
$$

We see $a_2 = \frac{3}{2}.$
This makes $a_{3} = \frac{4}{3}$


$a_0, a_1, a_2, a_3 = 1, 1, \frac{3}{2}, \frac{4}{3}$.