

Recall that the hyperbolic cosine function is defined as $\cosh(x)=\dfrac{e^x+e^{-x}}{2}$. Find the Taylor series about $x=0$, along with its radius of convergence, for $\cosh(x)$.

First, we find the first derivative of $f(x) = \cosh(x) = \dfrac{e^x+e^{-x}}{2}$

$$
\begin{align*}
\frac{d}{dx} \left(\dfrac{e^x+e^{-x}}{2}\right) &= \frac{1}{2} \cdot \frac{d}{dx} \left(e^x+e^{-x}\right) \\
&= \frac{1}{2} \cdot \frac{d}{dx} \, e^x + \frac{d}{dx} \, e^{-x} \\
&= \frac{1}{2} \cdot \left(e^x - e^{-x}\right) \\
\end{align*}
$$

Oddly enough, this happens to be $\sinh(x)$. Now, the value of $f'(0) = 0.$

Now, we move on to finding $f''(x)$. However, if we look back at our process of finding $f'(x)$, we find that $f(x) = \cosh(x)$, $f'(x) = \sinh(x)$, $f''(x) = \cosh(x)$ and so on. This makes our Taylor series:
$$
1+\frac{1}{2}x^{2}+\frac{1}{24}x^{4}+\frac{1}{720}x^{6}+\frac{1}{40320}x^{8} \ \cdots
$$
or
$$
1+\frac{1}{2!}x^{2}+\frac{1}{4!}x^{4}+\frac{1}{6!}x^{6}+\frac{1}{8!}x^{8} \ \cdots
$$