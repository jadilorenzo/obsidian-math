a) Use Taylor Polynomial approximation to show that the solutions of $x^2 = \cos x$ are approximately $\pm \sqrt{\frac23}$.  

We first take the 2nd-degree Taylor Polynomial:
$$1 - \frac{1}{2}x^2$$
and set it equal to $x^2$.
$$
\begin{align*}
1 - \frac{1}{2}x^2 &= x^2 \\
1  &= \frac{3}{2}x^2 \\
\frac{2}{3}  &= x^2 \\
\sqrt{ \frac{2}{3} }  &= x \\
\end{align*}$$

b) Find a reasonable bound for the maximum error of this approximation. (Notice that we're bounding the error in $x$ in this problem!)

$\left| \frac{M}{(n+1)!}(c-a)^{n+1} \right|$ where $M = f(x)$