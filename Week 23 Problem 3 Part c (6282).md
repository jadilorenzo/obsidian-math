Can you generalize to find solutions to the equation $y^{(n)} = y$?
If $y=c_1e^{c_2x}$, then $$
\begin{align*}
y^{(n)} &= c_1c_2^n e^{c_2x} \\
c_1c_2^ne^{c_2x} &= c_1e^{c_2x} \\
c_{2}^n &= 1.
\end{align*}$$
The only real solution to this is $c_{2} = 1$. However, there are many imaginary solutions such as $\omega = -\frac{1}{2}+\frac{\sqrt{ 3 }}{2}$ makes $\omega^3 =1.$ Of course, we don't usually write $e^{c_{2}}$ with an imaginary. We can rewrite $c_{1}e^{c_{2}x}$ with the complex term $a+bi$ for $c_2$

$$c_{1}e^{(a + bi)x} = c_{1} \left( e^{ax} \cos(bx) + i e^{ax} \sin(bx) \right)$$