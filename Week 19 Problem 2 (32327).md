A circle of radius 2 rolls along a flat surface at a constant rate, as shown below. A point which has a distance of 3 from the center of the circle is fixed with respect to the circle.  
  
Let $A$ be the midpoint of the arc, and let $B$ be a point where the path of the point intersects the surface. Let $v_A$ and $v_B$ be the speeds of the point at $A$ and $B,$ respectively. Compute $\frac{v_A}{v_B}.$
We know the formula for the trajectory of the point at the radius $2$ is $$\left(4\pi t\ -\ 2\sin\left(2\pi t\right),\ 2-\ 2\cos\left(2\pi t\right)\right)$$
With some experimentation and careful reasoning, we see the path of our point is $$
\begin{align*}
u(t) &= 6\pi t\ -\ 3\sin\left(3\pi t\right) \\ 
v(t) &= 2 - 3\cos\left(3\pi t\right).
\end{align*}$$
We know point $A$ occurs at $x=2\pi$. However, we do not know the $x$-coordinate of $B$. We know $y = 0 = 6\pi t\ -\ 3\sin\left(3\pi t\right)$.
$$
\begin{align}
0 &= 6\pi t\ -\ 3\sin\left(3\pi t\right) \\
t &= \frac{2 \pi - \cos^{-1}\frac{2}{3}}{3\pi}
\end{align}
$$
Thus $B$ occurs at $t= \frac{2 \pi - \cos^{-1}\frac{2}{3}}{3\pi} \approx 0.57742.$ 


Now we must find the $x$ and $y$ velocities at $A$. Point $A$ occurs at $x=2\pi$.
$$
\begin{align*}
6\pi t - 3\sin(3\pi t) &= 2\pi \\
t &= \frac{1}{3}
\end{align*}
$$
We then take the derivative of 
$$\begin{align*}
u(t) &= 6\pi t - 3\sin(3\pi t) \\ 
v(t) &= 2 - 3\cos(3\pi t)\\
u'(t) &= 6\pi - 9\pi\cos(3\pi t) \\ 
v'(t) &= 9\pi\sin(3\pi t)
\end{align*}$$
$$\begin{align*}
u'\left( \frac{1}{3} \right) &= 6\pi - 9\pi\cos(\pi) = 15\pi\\ 
v'\left( \frac{1}{3} \right) &= 9\pi\sin(\pi) = 0
\end{align*}$$
Point $A$ is being drawn at $15\pi$ units horizontally per second.

Now on to point $B$, which is drawn at $t= \frac{2 \pi - \cos^{-1}\frac{2}{3}}{3\pi} \approx 0.57742.$ 
$$\begin{align*}
u'\left(\frac{2 \pi - \cos^{-1}\frac{2}{3}}{3\pi} \right) &= 6\pi - 9\pi\cos\left(3\pi \left(\frac{2 \pi - \cos^{-1}\frac{2}{3}}{3\pi} \right)\right) = 0\\ 
v'\left(\frac{2 \pi - \cos^{-1}\frac{2}{3}}{3\pi} \right) &= 9\pi\sin\left(3\pi \left(\frac{2 \pi - \cos^{-1}\frac{2}{3}}{3\pi} \right)\right) = -3\pi \sqrt{ 5 }
\end{align*}$$
Thus, point $B$ is being drawn at $-3\pi \sqrt{ 5 }$ units vertically per second.


The question asks for $\frac{v_A}{v_B}.$
$$
\frac{v_A}{v_B} = \frac{15\pi}{-3\pi \sqrt{ 5 } } = -\frac{5}{\sqrt{ 5 }} = \boxed-\sqrt{ 5 }
$$