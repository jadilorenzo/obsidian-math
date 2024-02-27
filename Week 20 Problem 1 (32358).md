
The graph of $r = 1 + \sin \theta$ is drawn. The tangent to this graph at $\theta = \frac{\pi}{4}$ is drawn. Find the $x$-intercept of this tangent.

The equation for a line that goes through $(0,0)$ at angle $\theta$ is $$y = \tan(\theta)x.$$
Conversions:
$$
(r, \theta) = \left(\sqrt{ x^2 +y^2 }, \tan^{-1}\left( \frac{y}{x} \right)\right)
$$

At $\frac{\pi}{4}$, $r = 1 + \frac{\sqrt{ 2 }}{2}.$ Therefore, 
$$
\begin{align*}
1 + \frac{\sqrt{ 2 }}{2} &= \sqrt{ x^2 + y^2 } \\
\left( 1 + \frac{\sqrt{ 2 }}{2} \right)^2 &= x^2 + y^2 \\
\end{align*}
$$
And $$
\begin{align*}
\frac{\pi}{4} &= \tan^{-1}\left( \frac{y}{x} \right) \\
1 &= \frac{y}{x} \\
x &= y \\
\end{align*}
$$
Solving for $x$ first, we get
$$
\begin{align*}
\left( 1 + \frac{\sqrt{ 2 }}{2} \right)^2 &= 2x^2 \\
\sqrt{ 2 } + \frac{3}{2} &= 2x^2 \\
\frac{\sqrt{ 2 }}{2} + \frac{3}{4} &= x^2 \\
\frac{2\sqrt{ 2 } + 3}{4} &= x^2 \\
\frac{\sqrt{ 2\sqrt{ 2 } + 3}}{2} &= x \approx 1.2071067811866. \\
\end{align*}
$$
This means our $(x, y)$ coordinate is $(1.207106, 1.207106).$ 
Now, we must find a function for $y$ in terms of $\theta$
$$y =\sin\left(\theta\right)\left(1 + \sin\theta\right).$$
$$
\frac{dy}{d\theta} = \cos \theta \cdot(2\sin \theta+1)
$$
The $y$ derivative of this function at $\frac{\pi}{4}$ is:
$$
y' = \frac{\sqrt{ 2 }}{2} + 1.
$$
Now let's do the same for the $x$ derivative.
$$
x=\cos\left(\theta\right)\left(1+\sin\theta\right)
$$
