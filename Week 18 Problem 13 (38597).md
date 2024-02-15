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
$$f(x) = \displaystyle\sum_{n=1}^{\infty}\frac{2^{n}n!}{\frac{\left(2\left(n+1\right)\right)!}{2^{\left(n+1\right)}\left(n+1\right)!}}x^{\left(2n\ -1\right)} $$which can be simplified to:
$$\sum_{n=1}^{\infty}\frac{2^{1 + 2n} \cdot (1 + n) \cdot (n!)^2}{(2 \cdot (1 + n))!} x^{\left(2n\ -1\right)}
.$$

However, I do **not** need this as we can take the derivative term by term.

(a) Prove that $(1 - x^2) f'(x) = 1 + xf(x).$  

$$
\begin{align*}
f(x) &= x + \frac{2}{3} x^3 + \frac{2 \cdot 4}{3 \cdot 5} x^5 + \dots + \frac{2 \cdot 4 \dotsm 2n}{3 \cdot 5 \dotsm (2n + 1)} x^{2n + 1} + \dotsb \\
f'(x) &= 1+2x^2+\frac{2\cdot4}{3}x^4+\dfrac{2\cdot4\cdot6}{3\cdot5}x^6+...+\frac{2\cdot4\cdots2n}{3\cdot5\cdots(2n-1)}x^{2n}
\end{align*}
$$
Plugging this into the original equation for part a) ...
$$(1 - x^2) f'(x) = 1 + xf(x)$$
$$
\begin{align*}
(1 - x^2) \left( 1+2x^2+\dfrac{2\cdot4}{3}x^4+\dfrac{2\cdot4\cdot6}{3\cdot5}x^6 + \dotsb \dfrac{2\cdot4\cdots2n}{3\cdot5\cdots(2n-1)}x^{2n} \dotsm \right) 
&= \\ 1 + x \cdot 
\left(x + \frac{2}{3} x^3 + \frac{2 \cdot 4}{3 \cdot 5} x^5 + \dots + \frac{2 \cdot 4 \dotsm 2n}{3 \cdot 5 \dotsm (2n + 1)} x^{2n + 1} \dotsm \right) \\ \\

\left( 1+2x^2+\frac{2\cdot4}{3}x^4+\frac{2\cdot4\cdot6}{3\cdot5}x^6 + \dotsb \dfrac{2\cdot4\cdots2n}{3\cdot5\cdots(2n-1)}x^{2n} \dotsm \right) - \\ 
\left( x^2+2x^4+\dfrac{2\cdot4}{3}x^6+\frac{2\cdot4\cdot6}{3\cdot5}x^8 + \dotsb \frac{2\cdot4\cdots2n}{3\cdot5\cdots(2n-1)}x^{2n + 2} \dotsm \right) &= \\

1 + \left(2x^2 - x^2\right) + \left(\dfrac{2\cdot4}{3}x^4 - 2x^4 \right) + \left(\dfrac{2\cdot4\cdot6}{3\cdot5}x^6 - \dfrac{2\cdot4}{3}x^6 \right) \dotsm &= \\

1 + x^2 + \dfrac{2}{3}x^4 + \dfrac{2\cdot4}{3\cdot5}x^6 + \dotsm 
+ \dfrac{2\cdot4\cdots2(n-1)}{3\cdot5\cdots(2n-1)}x^{2n}
&= \\
\end{align*}
$$
And we know that...
$$1 + x^2 + \dfrac{2}{3}x^4 + \dfrac{2\cdot4}{3\cdot5}x^6 + \dotsm + \dfrac{2\cdot4\cdots2(n-1)}{3\cdot5\cdots(2n+1)}x^{2n} =1 + x \left(x + \frac{2}{3} x^3 + \frac{2 \cdot 4}{3 \cdot 5} x^5 + \dots + \frac{2 \cdot 4 \dotsm 2n}{3 \cdot 5 \dotsm (2n + 1)} x^{2n + 1} + \dotsb\right) $$

b) Prove that $f(x) = \frac{\arcsin x}{\sqrt{1 - x^2}}.$

Firstly, we can't help but notice that $\displaystyle\int\dfrac{1}{\sqrt{1-x^2}}\,dx=\arcsin(x).$ 
Since we know
$$(1 - x^2) f'(x) = 1 + xf(x),$$
we can set
$$g(x) = \sqrt{1 - x^2} f(x).$$
$$g'(x) =  \frac{(1 - x^2) f'(x) - x f(x)}{\sqrt{1 - x^2}}$$
This works out nicely, we know the numerator is $1$ so
$$g'(x) =  \frac{1}{\sqrt{1 - x^2}}$$
When we integrate this, we get
$$g(x) = \arcsin(x)$$
And then because
$$\arcsin(x)= \sqrt{1 - x^2} f(x),$$
$$f(x) = \boxed{ \frac{\arcsin(x)}{\sqrt{ 1 - x^2 }}}$$
