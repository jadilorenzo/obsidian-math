[asy]
unitsize(1.5 cm);

real a = 0.8;
pair O, P;

O = (0,0);
P = (1,1.5) + dir(20);

draw(arc((1,1.5),1,80,-40),red);
draw(O--interp(O,P,1.5));
draw(O--(2,0));
draw((P + dir(-70))--(P + dir(110)));
draw(dir(110)--dir(-70));

label("$r = f(\theta)$", (1,1.5) + dir(80), W, red);
label("$\theta$", (0.5,0.2));
label("$\alpha$", P + (0.1,0.3));
label("$\alpha$", (0.1,0.3));
dot("$O$", O, W);
dot("$P = (f(\theta), \theta)$", P, E);
[/asy]
![](https://latex.artofproblemsolving.com/e/c/4/ec451c834b3081fa63930080102b973879ffc395.png)
We are trying to prove that $$\tan \alpha = \frac{f(\theta)}{f'(\theta)}.$$To do this, we draw a parallel line to the tangent line that goes through $P$. This means the slope of the line going through $O$ is $m = \tan(\alpha + \theta).$ Now we must find the slope of the tangent line that goes through $P$:
$$\frac{dy/d \theta}{dx/d \theta} = \frac{d\left( \sin\theta\cdot f(\theta) \right)}{d\left( \cos\theta\cdot f(\theta) \right) } = \frac{f(\theta) \cos \theta + f'(\theta) \sin \theta}{- f(\theta)\sin \theta + f'(\theta) \cos \theta}.$$

Since these lines are parallel, we know that 
$$\begin{align*}
\frac{f(\theta) \cos \theta + f'(\theta) \sin \theta}{- f(\theta)\sin \theta + f'(\theta) \cos \theta} &= \tan(\alpha + \theta) \\
{f(\theta) \cos \theta + f'(\theta) \sin \theta} &= \tan(\alpha + \theta) \left( {- f(\theta)\sin \theta + f'(\theta) \cos \theta} \right) 
\end{align*}$$
