The path of a general cycloid is parameterized by $x = r(t - \sin t)$ and $y = r(1 - \cos t).$

(a) Find the length of one arch of the cycloid. (An _arch_ is the portion of the cycloid between two consecutive points where it touches the $x$-axis.)  
  
(b) Let $L$ be the length you found in part (a). One end $A$) of a string of length $\frac{L}{2}$ is tied at $(0,0),$ and the other end $B$ is at $(\pi r,2r),$ wrapping around one-half of one arch of the cycloid.  
  
Prove that as the string is unwrapped, the point $B$ traces a path that is parameterized by $x = r(t + \sin t)$ and $y = r(3 + \cos t).$ (This path is, in fact, congruent to an arch of the original cycloid.)  

(a)
The parametric arc length formula is $$\int_{a}^b \sqrt{ (u'(t))^2 + (v'(t))^2 } \, dt .$$
Our equation is 
$$\begin{align*}
u(t)&=r(t-\sin t)\\
v(t)&=r(1-\cos t)
\end{align*}$$$$\begin{align*}
u'(t)&=r(1-\cos t)\\
v'(t)&=r(\sin t)
\end{align*}$$
Therefore for the arc length from $0 \to 2\pi$ is
$$
\begin{align*}
\int_{0}^{2\pi} \sqrt{ (r(1-\cos t))^2 + (r(\sin t))^2 } \, dt = 8r
\end{align*}
$$

(b)