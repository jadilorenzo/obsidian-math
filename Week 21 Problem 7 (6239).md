Let $f : [0,1] \rightarrow [0,1]$ be a continuous function (not necessarily differentiable) such that $f(f(x)) = 1$ for all $x \in [0,1].$ Prove that
$$\int_0^1 f(x)\,dx > \frac34.$$

Let us begin by splitting this integral and setting the minimum of $f(x)$ to $c$ between $[0, 1]$.
$$\int_0^1 f(x) \, dx = \int_0^c f(x) \, dx + \int_c^1 f(x) \, dx,$$Because $[c,1]$ is in the domain of $f$, then we can simplify $\displaystyle\int_c^1 f(x) \, dx$ to $(1-c)$.
Rearranging we get:
$$\int_0^c f(x)\,dx + 1 - c > \frac34.$$