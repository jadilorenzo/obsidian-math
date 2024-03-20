Obviously $y = e^x$ is a solution to $y''' = y$. Show that $\displaystyle y = e^{-\frac{x}{2}}\cos\left(\frac{\sqrt3}{2}x\right)$ is also a solution. 

Note that if $\omega = -\dfrac12 + \dfrac{\sqrt3}{2}i$, then $\omega^3 = 1$. Why does this imply that the complex function $y = e^{\omega x}$ is a solution to $y''' = y$?

$$
\begin{align*}
y &= e^{-\frac{x}{2}}\cos\left(\frac{\sqrt3}{2}x\right) \\
y' &= -\frac{1}{2}e^{-\frac{x}{2}}\cos \left(\frac{\sqrt{3}x}{2}\right)-\frac{\sqrt{3}}{2}e^{-\frac{x}{2}}\sin \left(\frac{\sqrt{3}x}{2}\right) \\
y'' &= -\frac{1}{2}e^{-\frac{x}{2}}\cos \left(\frac{\sqrt{3}x}{2}\right)+\frac{\sqrt{3}}{2}e^{-\frac{x}{2}}\sin \left(\frac{\sqrt{3}x}{2}\right) \\
y''' &= -\frac{1}{2}\left(-\frac{1}{2}e^{-\frac{x}{2}}\cos \left(\frac{\sqrt{3}x}{2}\right)-\frac{\sqrt{3}}{2}e^{-\frac{x}{2}}\sin \left(\frac{\sqrt{3}x}{2}\right)\right) \\ &+\frac{\sqrt{3}}{2}\left(-\frac{1}{2}e^{-\frac{x}{2}}\sin \left(\frac{\sqrt{3}x}{2}\right)+\frac{\sqrt{3}}{2}e^{-\frac{x}{2}}\cos \left(\frac{\sqrt{3}x}{2}\right)\right) \\
y''' &= -\frac{1}{2}\left(-\frac{1}{2}e^{-\frac{x}{2}}\cos \left(\frac{\sqrt{3}x}{2}\right)-\frac{\sqrt{3}}{2}e^{-\frac{x}{2}}\sin \left(\frac{\sqrt{3}x}{2}\right)\right) \\ &+\frac{\sqrt{3}}{2}\left(-\frac{1}{2}e^{-\frac{x}{2}}\sin \left(\frac{\sqrt{3}x}{2}\right)+\frac{\sqrt{3}}{2}e^{-\frac{x}{2}}\cos \left(\frac{\sqrt{3}x}{2}\right)\right) \\
y''' &= e^{-\frac{x}{2}}\cos \left(\frac{\sqrt{3}x}{2}\right)
\end{align*}$$