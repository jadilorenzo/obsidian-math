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
$$\int_1^\infty \frac{\log (x)^m}{x^n}dx=-\dfrac{m}{1-n}\int_1^\infty\dfrac{\log(x)^{m-1}}{x^{n}}\,dx.$$

