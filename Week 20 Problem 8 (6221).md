Find a formula for the area of the triangle with vertices (in polar coordinates) $(r_1,\theta_1)$, $(r_2, \theta_2)$, and $(r_3,\theta_3)$.

We'll call these points $T_{1}$, $T_{2}$, and $T_{3}.$
First, let's add a fourth point $O$ at the origin $(r, \theta) = (0,0)$ which we will assume is inside the triangle.

Now it will likely be easier to find the area between:  $T_{1}$, $T_{2}$, and $O$;  $T_{1}$, $T_{3}$, and $O$; and  $T_{3}$, $T_{2}$, and $O$ individually.

We use the SAS formula to determine the length of the third side of the sub-triangle.
Using triangle between $T_{1}$, $T_{2}$, and $O$ as an example...
$$c = \sqrt{ r_{1}^2 + r_{2}^2 - 2r_{1}r_{2}\cos |\theta_{1}-\theta_{2}| }$$
where $c$ is the length of the far side. Now using Heron's formula... 
$$A = \frac{1}{4} \sqrt{ 4a^2b^2 - (a^2 + b^2 - c^2)^2 }$$
Substituting in $c$ and the proper values for $a$ and $b$:
$$A = \frac{1}{4} \sqrt{ 4r_{1}^2r_{2}^2 - \left(r_{1}^2 + r_{2}^2 - \left( r_{1}^2 + r_{2}^2 - 2r_{1}r_{2}\cos |\theta_{1}-\theta_{2}| \right)\right)^2 }$$
which simplifies to:
$$\frac{1}{2}\sqrt{r_1r_2\left(1-r_1r_2\cos ^2\left(\left|θ_1-θ_2\right|\right)\right)}$$