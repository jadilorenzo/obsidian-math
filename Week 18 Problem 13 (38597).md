Let  
$$f(x) = x + \frac{2}{3} x^3 + \frac{2 \cdot 4}{3 \cdot 5} x^5 + \dots + \frac{2 \cdot 4 \dotsm 2n}{3 \cdot 5 \dotsm (2n + 1)} x^{2n + 1} + \dotsb$$ on the interval $(-1,1)$ of convergence of the defining series.  
  
(a) Prove that $(1 - x^2) f'(x) = 1 + xf(x).$  
(b) Prove that $f(x) = \frac{\arcsin x}{\sqrt{1 - x^2}}.$


Let's put $f(x)$ in summation form:

We first try to get the **numerator**:
The pattern is: $$1, 2, 8, 48, 384, 3840$$Which means it's $$2^{n}n!$$ for the $n$th term.

The **denominator** sequence is:
$$
1, 3, 15, 105, 945 \cdots
$$
which strongly reminds me of $$\frac{(2n)!}{2^n(n)}.$$However, this pattern is
$$1, 1, 3, 15, 105, 945 \cdots$$
So we subtract $1$ from $n$ giving us
$$\frac{\left(2\left(n+1\right)\right)!}{2^{\left(n+1\right)}\left(n+1\right)!}$$
This makes our whole sum...
$$f(x) = \displaystyle\sum_{n=1}^{\infty}\frac{2^{n}n!}{\frac{\left(2\left(n+1\right)\right)!}{2^{\left(n+1\right)}\left(n+1\right)!}}x^{\left(2n\ -1\right)} $$.