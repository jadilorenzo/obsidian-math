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

The reasonable bound for the maximum error of this approximation is:  
$$\left|\frac{\sin(x_0)x^3}{6}\right|,$$
when $0\le x_0 \le x$ such that $\sin(x_0)$ is maximized. In part a), we found that $x \approx \sqrt{\frac{2}{3}}$, and $\sin(x_0)$ is maximized at this value.  
We get,  
$$\frac{\sin\left(\sqrt{\frac{2}{3}}\right)\cdot \left(\sqrt{\frac{2}{3}}\right)^3}{3!} \approx 0.066666...$$So, this is our reasonable bound.