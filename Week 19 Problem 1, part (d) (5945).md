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
u_{o}(t) &= c_{0} \cos(t) + h\\
v_{o}(t) &= c_{1} \sin(t) +k
\end{align*}$$
we get a graph of an ellipse 


![[Screenshot 2024-02-19 at 2.29.06 PM.png]]

$$(u(t) \cdot \cos{\theta} - v(t) \cdot \sin{\theta}, u(t) \cdot \sin{\theta} + v(t) \cdot \cos{\theta})$$
$$\left(u(t)\cdot\cos\left(a\right)-v(t)\cdot\sin\left(a\right),\ u(t)\cdot\sin\left(a\right)+v(t)\cdot\cos\left(a\right)\right)$$
$$\left(\left(c_{0}\cos\left(t\right)\right)\cdot\cos\left(a\right)-\left(c_{1}\sin\left(t\right)\right)\cdot\sin\left(a\right)+h,\ u(t)\cdot\sin\left(a\right)+\left(c_{1}\sin\left(t\right)\right)\cdot\cos\left(a\right)\right)$$
$$
\begin{align*}
\left(\left(c_{0}\cos\left(t\right)\right)\cdot\cos\left(a\right)-\left(c_{1}\sin\left(t\right)\right)\cdot\sin\left(a\right)+h, \ 
\left(c_{0}\cos\left(t\right)\right)\cdot\sin\left(a\right)+\left(c_{1}\sin\left(t\right)\right)\cdot\cos\left(a\right)\ +k\right)
\end{align*}
$$