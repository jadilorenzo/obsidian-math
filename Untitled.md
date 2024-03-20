In order to tackle this problem, we can first create an expression for points $A$ and $B$ in terms of $f(x)$ . With those, we can then create an equation for $P$ being the midpoint of $\overline{AB}$.

The coordinates of a point $P$ on $f(x)$ are $(p,f(p))$. As the slope of $f(x)$ at any point $P$ is $f'(p)$, we can create a point-slope form equation of the tangent line, giving us $y-f(p)=f'(p)(x-p)$, or in standard form$$y=f'(p)x-f'(p)p+f(p).$$Because $A$ is on the intersection of the tangent line and the $x$ axis, the $y$ coordinate will be $0$.

This means that the $x$ coordinate of $A$ can be represented as
\begin{align*}
0&=f'(p)x-f'(p)p+f(p)\\
x&=\dfrac{f'(p)p-f(p)}{f'(p)}.\\
\end{align*}
Therefore, the coordinates of $A$ are $\left(\dfrac{f'(p)p-f(p)}{f'(p)},0\right)$.

Moving on to $B$, we can apply the same strategy, but this time set $x=0$ as this is the intersection with the $y$-axis. This lends us
\begin{align*}
y&=-f'(p)p+f(p),\\
\end{align*}
Which means the coordinates of $B$ are $\left(0,-f'(p)p+f(p)\right)$.

As $P$ is the midpoint of $A$ and $B$ and these fall on the $x$ and $y$ axis respectively, the $x$ coordinate of $A$ is double the $x$ coordinate of $P$, and the $y$ coordinate of $B$ is double the $y$ coordinate of $P$. This means that
\begin{align*}
A&=(2p,0)\\
B&=(0,2f(p)).\\
\end{align*}
We now have two different expressions for each of the coordinates of $A$ and $B$! Setting the meaningful components equal, we obtain the two equations
\begin{align*}
2p&=\dfrac{f'(p)p-f(p)}{f'(p)}\\
2f(p)&=-f'(p)p+f(p).\\
\end{align*}
Using the second equation, we can determine an expression for $f'(p)$ in terms of $p$ and $f(p)$, giving us $f'(p)=-\dfrac{f(p)}p$.

While we could solve this with separation of variables, we can instead substitute this value into the first equation, granting
\begin{align*}
2p&=\dfrac{\left(-\dfrac{f(p)}p\right)p-f(p)}{\left(-\dfrac{f(p)}p\right)}\\
2p&=\dfrac{-2f(p)}{\left(-\dfrac{f(p)}p\right)}\\
2p&=2p\\
\end{align*}