Evaluate $\displaystyle \int_1^\infty \left(\frac{\log x}{x}\right)^{2011}dx$.

Let's try and tackle a generic version of this problem to see if we can find a pattern.
Our generic integral is $\displaystyle \int_{1}^{\infty} \frac{\log(x)^m}{x^n} \, dx$.

Using integration by parts, we set $u = \log(x)^m$  and $dv = x^{-n}\,dx$ which makes $v = \frac{1}{(n-1)x^n}$ and $du = \frac{m \log(x)^{m-1}}{x}$. So for the whole integral, we get:
$$
\int_1^\infty \frac{\log (x)^m}{x^n}\,dx = \left.-\frac{(\log x)^m}{(n-1)x^{n-1}}\right|^{\infty}_{1}+\int_1^{\infty}\frac{m(\log x)^{m-1}}{(n-1)x^{n}}
$$Since  $\log(1) = 0$,$$
\left.-\frac{(\log x)^m}{(n-1)x^{n-1}}\right|^{\infty}_{1} = \lim_{ x \to \infty } \left( -\frac{(\log x)^m}{(n-1)x^{n-1}} \right) 
$$
And since we know $x^{n-1}$ increases faster than $\log(x)^m$, this limit approaches $0$.
$$\begin{align}
\int_1^\infty \frac{\log (x)^m}{x^n}\,dx &= \int_1^{\infty}\frac{m(\log x)^{m-1}}{(n-1)x^{n}} \\
&= \frac{m}{n-1} \int_1^{\infty}\frac{(\log x)^{m-1}}{x^{n}}
\end{align}$$
Aha! Now we see the pattern.
$$\begin{align}
&= \left( \frac{m}{n-1} \right) \cdot\left( \frac{m}{n-2} \right) \cdot  \left( \frac{m}{n-3} \right) \cdots\int_1^{\infty}\frac{(\log x)^{0}}{x^{n}} \\ \\
&= \frac{m^m}{n!} \int_1^{\infty}\frac{(\log x)^{0}}{x^{n}} \\
&= \frac{m^m}{n!} \int_1^{\infty}\frac{1}{x^{n}} \\ 
&= \frac{m^m}{n!} \left( \frac{1}{n-1} \right)
\end{align}$$
In our case $m = n = 2011$, this means our final answer is
$$\frac{m^m}{n!} \left( \frac{1}{n-1} \right) = \boxed{\frac{2011^{2011}}{2011! \cdot 2010}}$$