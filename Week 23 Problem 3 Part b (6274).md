Obviously $y = e^x$ is a solution to $y''' = y$. Show that $\displaystyle y = e^{-\frac{x}{2}}\cos\left(\frac{\sqrt3}{2}x\right)$ is also a solution. 

Note that if $\omega = -\dfrac12 + \dfrac{\sqrt3}{2}i$, then $\omega^3 = 1$. Why does this imply that the complex function $y = e^{\omega x}$ is a solution to $y''' = y$?

$$
\begin{align*}
y &= e^{-\frac{x}{2}}\cos\left(\frac{\sqrt3}{2}x\right) \\
y' &= -\frac{1}{2}e^{-\frac{x}{2}}\cos \left(\frac{\sqrt{3}x}{2}\right)-\frac{\sqrt{3}}{2}e^{-\frac{x}{2}}\sin \left(\frac{\sqrt{3}x}{2}\right) \\
y'' &= -\frac{1}{2}e^{-\frac{x}{2}}\cos \left(\frac{\sqrt{3}x}{2}\right)+\frac{\sqrt{3}}{2}e^{-\frac{x}{2}}\sin \left(\frac{\sqrt{3}x}{2}\right) \\
y''' &= -\frac{1}{2}\left(-\frac{1}{2}e^{-\frac{x}{2}}\cos \left(\frac{\sqrt{3}x}{2}\right)-\frac{\sqrt{3}}{2}e^{-\frac{x}{2}}\sin \left(\frac{\sqrt{3}x}{2}\right)\right) \\ &+\frac{\sqrt{3}}{2}\left(-\frac{1}{2}e^{-\frac{x}{2}}\sin \left(\frac{\sqrt{3}x}{2}\right)+\frac{\sqrt{3}}{2}e^{-\frac{x}{2}}\cos \left(\frac{\sqrt{3}x}{2}\right)\right) \\
y''' &= e^{-\frac{x}{2}}\left(-\frac{1}{2}\left(-\frac{1}{2} \cos \left(\frac{\sqrt{3}x}{2}\right)-\frac{\sqrt{3}}{2}\sin \left(\frac{\sqrt{3}x}{2}\right)\right) +\frac{\sqrt{3}}{2}\left(-\frac{1}{2}\sin \left(\frac{\sqrt{3}x}{2}\right)+\frac{\sqrt{3}}{2}\cos \left(\frac{\sqrt{3}x}{2}\right)\right)\right) \\
y''' &= e^{-\frac{x}{2}}\left(\frac{1}{4} \cos \left(\frac{\sqrt{3}x}{2}\right)+\frac{\sqrt{3}}{4}\sin \left(\frac{\sqrt{3}x}{2}\right) -\frac{\sqrt{3}}{4}\sin \left(\frac{\sqrt{3}x}{2}\right)+\frac{3}{4}\cos \left(\frac{\sqrt{3}x}{2}\right)\right) \\
y''' &= e^{-\frac{x}{2}}\left(\frac{1}{4} \cos \left(\frac{\sqrt{3}x}{2}\right)+\frac{3}{4}\cos \left(\frac{\sqrt{3}x}{2}\right)\right) \\
y''' &= e^{-\frac{x}{2}}\cos \left(\frac{\sqrt{3}x}{2}\right)
\end{align*}$$

Since if $\omega = -\dfrac12 + \dfrac{\sqrt3}{2}i$, then $\omega^3 = 1$, this implies the ratio of one to be present in the third-order linear differential equation, which it is. 

$e^{ax} \cos(bx) + i e^{ax} \sin(bx)$