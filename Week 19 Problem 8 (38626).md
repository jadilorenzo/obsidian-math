The path of a general cycloid is parameterized by $x = r(t - \sin t)$ and $y = r(1 - \cos t).$

(a) Find the length of one arch of the cycloid. (An _arch_ is the portion of the cycloid between two consecutive points where it touches the $x$-axis.)  
  
(b) Let $L$ be the length you found in part (a). One end $A$) of a string of length $\frac{L}{2}$ is tied at $(0,0),$ and the other end $B$ is at $(\pi r,2r),$ wrapping around one-half of one arch of the cycloid.  
  
Prove that as the string is unwrapped, the point $B$ traces a path that is parameterized by $x = r(t + \sin t)$ and $y = r(3 + \cos t).$ (This path is, in fact, congruent to an arch of the original cycloid.)  

(a)
The parametric arc length formula is $$\int_{a}^b \sqrt{ (u'(t))^2 + (v'(t))^2 } \, dt .$$
Our equation is 
$$\begin{align*}
u_{1}(t)&=r(t-\sin t)\\
v_{1}(t)&=r(1-\cos t)
\end{align*}$$$$\begin{align*}
u'_{1}(t)&=r(1-\cos t)\\
v'_{1}(t)&=r(\sin t)
\end{align*}$$
Therefore for the arc length from $0 \to 2\pi$ is
$$
\begin{align*}
\int_{0}^{2\pi} \sqrt{ (r(1-\cos t))^2 + (r(\sin t))^2 } \, dt = 8r
\end{align*}
$$

(b)

Hint:

For part (b), suppose that the string touches the cycloid for $0 \le t \le u.$ Let $U = (r(u - \sin u), r(1 - \cos u)).$ Compute the length of the arc from $A$ to $U,$ and note that $BU$ is taut, so it is straight. Use this to compute the coordinates of $B$.

We'll break this problem into two parts 
1) Distance from $A$ to $U$
2) Distance from $U$ to $B$

Part 1)
$U$ is defined as $(u_{1}(u), v_{1}(u))$ for some $\pi \le u \le 3\pi$ so the distance between $A$ and $U$ is
$$
\begin{align*}
\int_{2\pi}^{u} \sqrt{ (r(1-\cos t))^2 + (r(\sin t))^2 } \, dt &= r\int_{2\pi}^{u} \sqrt{ (1-\cos t)^2 + (\sin t)^2 } \, dt \\
&=-4r\cos\left(\frac{t}{2}\right)+4r
\end{align*}
$$
(This final conversion works because we want arc length for $U$ points before $A$ as well as those after)

Part 2)
Now we must find the distance between $U$ and $B$. We are trying to prove the string connecting $A$, $U$ and $B$ goes along 
$$
\begin{align*}
u_{2}(t) &= r(t + \sin t) \\ 
v_{2}(t) &= r(3 + \cos t).
\end{align*}
$$
If this line does reach this path, its length will be a constant $4r$. This slope is
$$\frac{u_{1}(t) - u_{2}(t)}{v_{1}(t) - v_{2}(t)}
$$
$$
\begin{align*}
\frac{(1 - \cos t ) - (3 + \cos t)}{(t - \sin t) - (t+\sin t)} = \frac{-2 - 2\cos t}{ -2 \sin t} = \frac{1+\cos t}{\sin t} = \frac{1}{\tan \frac{t}{2}}
\end{align*}
$$
We plot this and it is the proper slope for such a line as $y-v_{2}\left(u\right)=\tan\left(\frac{u}{2}\right)^{-1}(x-u_{2}\left(u\right)).$ 
Now, we must find the length of $\overline{UB}$. Using a technique developed by our friend Pythagoras:
$$r\sqrt{ (1 + \cos t)^2 + (\sin t)^2 } = 4r \cos\left( \frac{t}{2} \right).$$

Wow! Since $$-4r\cos\left(\frac{t}{2}\right)+4r + 4r \cos\left( \frac{t}{2} \right) = 4r,$$ we have proved the problem statement.