Evaluate $\displaystyle \int_1^\infty \left(\frac{\log x}{x}\right)^{2011}dx$.

<div style='display: none'>
int u dv = uv - ind v du
</div>
Using integration by parts, we set $u = (\log x)^{2011}$  and $dv = x^{-2011}\,dx$ which means 
$$v = -2010^{-1}x^{-2010} = \frac{1}{-2010x^{2021}}$$
$$du = \frac{2011\log ^{2010}(x)}{x}$$
$$\int u \, dv =  uv - \int  v \, du $$
$$
\begin{align*}
\int_1^\infty \left(\frac{\log x}{x}\right)^{2011}dx = \left( \log^{2011}(x) \cdot -2010^{-1}x^{-2010}\right) \bigg|_1^{\infty} + \int \left(-2010^{-1}x^{-2010} \cdot \frac{2011\log ^{2010}(x)}{x}\right) \, dx 
\end{align*}
$$
The first half of this can be simplified to:
$$
\left( \log^{2011}(x) \cdot -2010^{-1}x^{-2010}\right) \bigg|_1^{\infty} = \lim_{ x \to \infty } \left( \log^{2011}(x) \cdot -2010^{-1}x^{-2010}\right)
$$ ($\log(1) = 0$)
$$
\begin{align}
\lim_{ x \to \infty } \left( \log^{2011}(x) \cdot -2010^{-1}x^{-2010}\right) = \frac{\log^{2011}(x)}{-2010x^{2010}}\
\end{align}
$$



Let's try and tackle a generic version of this problem to see if we can find a pattern.
Our generic integral is $\displaystyle \int_{1}^{\infty} \frac{\log(x)^m}{x^n} \, dx$.

Using integration by parts, we set $u = \log(x)^m$  and $dv = x^{-n}\,dx$ which makes $v = \frac{1}{(n-1)x^n}$ and $du = \frac{n \log(x)^{n-1}}{x}$. So for the whole integral, we get:
$$
\int_1^\infty \frac{\log (x)^m}{x^n}\,dx = \left.-\frac{(\log x)^m}{(n-1)x^{n-1}}\right|^{\infty}_{1}+\int_1^{\infty}\frac{m(\log x)^{m-1}}{(n-1)x^{n}}
$$Since  $\log(1) = 0$,$$
\left.-\frac{(\log x)^m}{(n-1)x^{n-1}}\right|^{\infty}_{1} = \lim_{ x \to \infty } \left( -\frac{(\log x)^m}{(n-1)x^{n-1}} \right) 
$$
$x^{n-1}$ increases faster than $\log(x)^m$.
$$\begin{align}
&= \int_1^{\infty}\frac{m(\log x)^{m-1}}{(n-1)x^{n}} \\
&= \frac{m}{n-1} \int_1^{\infty}\frac{(\log x)^{m-1}}{x^{n}}
\end{align}$$