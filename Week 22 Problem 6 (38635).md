The function $f(x),$ defined for $x \ge 0,$ has the following properties: 
- $f(x) \ge \sqrt{x}$ for all $x \ge 0.$ 
- The function $f(x)$ is increasing. 
- The area between the graph of $y = f(x)$ for $0 \le x \le a$ and the graph of $y = \sqrt{x}$ is equal to the area between the same part of the graph and the $y$-axis. (In other words, the red area is equal to the blue area.)  

(a) Find a differential equation that the function $f(x)$ satisfies. (In particular, this equation will involve $f(x)$ and $f'(x).$)
(b) Prove that $f(x) = 2 \sqrt{x} + kx$ for some constant $k.$

(a)
$$
\int_0^a f(a)-f(x)\,dx = \int_0^a f(x)-\sqrt{x} \, dx
$$
We know f(a) is a constant so
$$
\begin{align*}
af(a)-\int_0^af(x)\,dx &= \int_0^a f(x)-\sqrt{x} \, dx \\
af(a)-\int_0^af(x)\,dx &= \int_0^a f(x) \, dx - \int_0^a \sqrt{x} \, dx \\
a f'(a) + f(a) + \sqrt{ a } &= 2 f(a) \\
- f(a) + \sqrt{ a } &= - a f'(a) \\
af'(a) &= f(a)-\sqrt{a} \\
f'(a) &= \frac{f(a)-\sqrt{a}}{a}. \\
\end{align*}
$$

(b) 
Plugging in $f(x)=2\sqrt{x}+kx$ we get:
$$
\frac{d}{dx}\frac{1}{\sqrt{x}}+C = \frac{2\sqrt{x}+kx-\sqrt{x}}{x} = \frac{\sqrt{ x }}{x}+k = \frac{1}{\sqrt{x}}+k.
$$
