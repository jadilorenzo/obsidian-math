Let $f : [0,1] \rightarrow [0,1]$ be a continuous function (not necessarily differentiable) such that $f(f(x)) = 1$ for all $x \in [0,1].$ Prove that
$$\int_0^1 f(x)\,dx > \frac34.$$

Let us begin by splitting this integral and setting the minimum of $f(x)$ to $c$ between $[0, 1]$.
$$\int_0^1 f(x) \, dx = \int_0^c f(x) \, dx + \int_c^1 f(x) \, dx,$$Because $[c,1]$ is in the domain of $f$, then we can simplify $\int_c^1 f(x) \, dx$ to $(1-c)$. Because $f(f(x))=1$, we can also see that $\int_0^c f(x) \, dx = c^2.$
Rearranging we get:
$$c^2 + 1 - c = \left(c - \frac{1}{2} \right)^2 + \frac{3}{4}$$
We know $c$ can't be $\frac{1}{2}$ because this makes $f$ non-continuous. Therefore $$\int_0^1 f(x)\,dx > \frac34.$$