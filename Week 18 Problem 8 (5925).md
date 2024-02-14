Find the power series of the function $\sqrt{x+1}$ about $x=2$.

Let's call $f(x) = \sqrt{x+1}.$

$$
\begin{align*}
f'(x) &= \frac{1}{2 \cdot \sqrt{ x+1 }} \\
f''(x) &=  -\frac{1}{4 \cdot(x+1)^{3/2}}\\
f'''(x) &= \frac{3}{8\cdot(x+1)^{5/2}} \\
f''''(x) &= -\frac{15}{16 \cdot (x+1)^{7/2}}
\end{align*}
$$

$$f(2) = \sqrt{ 3 }$$
$$
\begin{align*}
f'(2) &= \frac{\sqrt{ 3 }}{6} \\
f''(2) &= -\frac{\sqrt{ 3 }}{36} \\
f'''(2) &= \frac{\sqrt{ 3 }}{72} \\
f''''(2) &= -\frac{ 5\cdot\sqrt{ 3 }}{432}
\end{align*}
$$




<div style='display: none'>
$$\displaystyle\sum_{n = 0} 3^{\frac{1}{2} - n} \binom{\frac{1}{2}}{n} (x - 2)^n = \displaystyle\sum_{n = 0} 3^{\frac{1}{2} - n} \frac{\frac{1}{2}!}{n! \left( n - \frac{1}{2} \right)!} (x - 2)^n $$
</div>