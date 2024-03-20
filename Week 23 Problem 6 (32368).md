The function $f(x),$ defined for $x > 0,$ is positive, differentiable, and decreasing. The function $f(x)$ has the following property: Let $P$ be a point on the graph, and draw the tangent to the graph at $P.$ Let the tangent meet the $x$-axis and $y$-axis at $A$ and $B,$ respectively. Then $P$ is always the midpoint of $\overline{AB}.$ 

Find all functions $f(x)$ that have this property.

<hr>

First, let's find $A$ and $B$ in terms of $f(x)$ . 

Assuming $P = (p, f(p)),$ $$\begin{align*}
A &= (2p,0) \\
B &= (0,2f(p)). \\
\end{align*}$$
Because tangent line must go through $(p, f(p))$ the tangent line at $P$ is $y - f(p) = f'(p)(x - p).$
This means the $x$-coordinate at $A$ (since $y = 0$) is $$
\begin{align*}
0 &= f'(p)x-f'(p)p+f(p)\\
x &= \frac{f'(p)p - f(p)}{f'(p)}.\\
\end{align*}
$$
The $y$-coordinate for $B$ is likewise $$y = -f'(p)p + f(p).$$

Combining these, we get $$
\begin{align*}
2f(p) &= -f'(p)p + f(p) \\
2p &= \frac{f'(p)p-f(p)}{f'(p)} \\
\end{align*}$$
We can get a first-order differential equation from the second equation alone.
$$
\begin{align*}
2p &= \frac{f'(p)p-f(p)}{f'(p)} \\
f'(p) &= \frac{f'(p)p-f(p)}{2p} \\
f'(p) &= \frac{f'(p)p}{2p} + \frac{-f(p)}{2p} \\
f'(p) &= \frac{f'(p)}{2} + \frac{-f(p)}{2p} \\
\frac{f'(p)}{2} &= \frac{-f(p)}{2p} \\
f'(p) &= \frac{-f(p)}{p} \\
\end{align*}
$$

Solving this differential equation we get $$f(x) = \frac{c_{1}}{a}$$ which also satisfies the equation for $B.$