Is it possible to write $x = f(x)g(x)$, where $f$ and $g$ are differentiable functions with $f(0) = g(0) = 0$? (If possible, find an example; if impossible, prove it.)

Taking the derivative of our original expression:
$$
\begin{align*}
x &= f(x)g(x) \\
1 &= f(x)g'(x) + f'(x)g(x) \\
\end{align*}
$$
plugging in $f(0)$ and $g(0)$, we get
$$
\begin{align*}
1 &= f(0)g'(0) + f'(0)g(0) \\
1 &= (0)g'(0) + f'(x)(0) \\
1 &= 0.
\end{align*}
$$
Therefore, it is impossible to write $x = f(x)g(x)$, where $f$ and $g$ are differentiable functions.