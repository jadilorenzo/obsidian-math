Write parametric equations for an ellipse with foci $(2,0)$ and $(3,1)$ passing through $(1,2).$

This circle must be centered on $\left(\frac{5}{2},\frac{1}{2}\right)$. Therefore we can tentatively define 
$$
\begin{align*}
u\left(t\right)&=c_{0}\cos(t)+\frac{5}{2} \\ v\left(t\right)&=c_{1}\sin(t)+\frac{1}{2}.
\end{align*}
$$
However, no matter what $c$ we use our function will never be slanted. Upon experimentation, if we assign $$v(t) = c_{0} \sin\left( t + \frac{\pi}{4} \right) + \frac{1}{2},$$
the ellipse takes on a near $45°$ slant. This is desirable because we want to place $(1,2)$ on the ellipse's edge and the foci on the major axis. However, our function is only *near* a $45°$ slant when we use $c$ values where $\frac{c_{0}}{c_{1}} \approx 1$. Therefore, it seems we have to use a different transformation method. 

Let's first see how we can translate an ellipse around the origin when it's centered on the origin. If we have
$$
\begin{align*}
u_{o}(t) &= c_{0} \cos(t)\\
v_{o}(t) &= c_{1} \sin(t)
\end{align*}
$$
as our original ellipse, our rotated ellipse for $\theta$ is
$$
(u_{o}(t) \cdot \cos{\theta} - v_{o}(t) \cdot \sin{\theta},\ u_{o}(t) \cdot \sin{\theta} + v_{o}(t) \cdot \cos{\theta})
$$But if we add our constants back in, 
$$\begin{align*}
u(t) &= c_{0} \cos(t) + h\\
v(t) &= c_{1} \sin(t) +k
\end{align*}$$
we get a graph of an ellipse rotated around the origin instead of its center. Thus we add $h$ and $k$ after the transformation to get our final result:
$$
\begin{align*}
u(t) &= \cos(\theta) (c_{0} \cos(t)) - \sin(\theta)(c_{1} \sin(t)) + h\\
v(t) &= \sin(\theta) (c_{1} \sin(t)) + \cos(\theta)(c_{0} \cos(t)) + k
\end{align*}
$$
Now all we have to do is assign our constants $c_{0}$, $c_{1}$, $h$, $k$  and $\theta$.
$$
\begin{align*}
c_{0} &= \sqrt{ 5 } &\text{ (major axis length)} \\
c_{1} &= \frac{3\sqrt{ 2 }}{2} &\text{ (minor axis length)} \\
c_{0} &= \frac{\pi}{4} &\text{ (angle of rotation)} \\
h &= \frac{5}{2} &\text{ (center x coordinate)} \\
k &= \frac{1}{2} &\text{ (center y coordinate)} \\
\end{align*}
$$
$$
\begin{align*}
u(t) &= \cos\left(\frac{\pi}{4}\right) \left(\sqrt{ 5 } \cos(t)\right) - \sin\left(\frac{\pi}{4}\right)\left(\frac{3\sqrt{ 2 }}{2} \sin(t)\right) + \frac{5}{2}\\
v(t) &= \sin\left( \frac{\pi}{4} \right) \left(\frac{3\sqrt{ 2 }}{2} \sin(t)\right) + \cos\left(\frac{\pi}{4}\right)\left(\sqrt{ 5 } \cos(t)\right) + \frac{1}{2}
\end{align*}
$$
Oddly enough, $\sin\left(\frac{\pi}{4}\right) = \cos\left(\frac{\pi}{4}\right)$
$$
\begin{align*}
u(t) &= \sin\left(\frac{\pi}{4}\right) \left(\sqrt{ 5 } \cos(t) - \frac{3\sqrt{ 2 }}{2} \sin(t)\right) + \frac{5}{2}\\
v(t) &= \sin\left( \frac{\pi}{4} \right) \left(\frac{3\sqrt{ 2 }}{2} \sin(t) +\sqrt{ 5 } \cos(t)\right) + \frac{1}{2}
\end{align*}
$$
for $t$ from $0 \to 2\pi.$