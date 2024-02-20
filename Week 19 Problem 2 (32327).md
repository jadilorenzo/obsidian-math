
Problem:

[Report Error](https://artofproblemsolving.com/class/3611-calculus/homework/19#)

A circle of radius 2 rolls along a flat surface at a constant rate, as shown below. A point which has a distance of 3 from the center of the circle is fixed with respect to the circle.  
  
![[asy]
unitsize(0.4 cm);
real a, b, t;
path cycloid;
a = 2;
b = 3;
cycloid = (0,a - b);
draw(Circle((0,a),a));
draw(Circle((8*pi,2),a));
draw((0,2)--(0,a - b));
draw((8*pi,2)--(8*pi,a - b));
draw((0,0)--(8*pi,0));
t = 8;
draw(Circle((t,a),a));
draw((t,a)--(t - b*sin(t/a), a - b*cos(t/a)));
for (t = 0; t <= 8*pi; t = t + 0.01) {
cycloid = cycloid--(t - b*sin(t/a), a - b*cos(t/a));
}
draw(cycloid,red);
dot((0,2));
dot((8*pi,2));
dot((0,-1));
dot((8*pi,-1));
t = 8;
dot((t,a));
dot((t - b*sin(t/a), a - b*cos(t/a)));
t = 2*pi;
dot("$A$", (t - b*sin(t/a), a - b*cos(t/a)), N);
t = 4*pi - 2*acos(2/3);
dot("$B$", (t - b*sin(t/a), a - b*cos(t/a)), SE);
[/asy]](https://latex.artofproblemsolving.com/3/5/9/359150633564d19dc96ed951be51fd356c773aa7.png)  
  
Let ![$A$](https://latex.artofproblemsolving.com/0/1/9/019e9892786e493964e145e7c5cf7b700314e53b.png) be the midpoint of the arc, and let ![$B$](https://latex.artofproblemsolving.com/f/f/5/ff5fb3d775862e2123b007eb4373ff6cc1a34d4e.png) be a point where the path of the point intersects the surface. Let ![$v_A$](https://latex.artofproblemsolving.com/1/0/d/10db40cc18d7471c355651971b33d25580f36e42.png) and ![$v_B$](https://latex.artofproblemsolving.com/8/a/b/8abdc09b48c2598712ceb4ce892b6c50cdb84632.png) be the speeds of the point at ![$A$](https://latex.artofproblemsolving.com/0/1/9/019e9892786e493964e145e7c5cf7b700314e53b.png) and ![$B,$](https://latex.artofproblemsolving.com/c/c/e/ccedc2f7ab3f66b36d3e0cf1536a3c801f01f421.png) respectively. Compute ![$\frac{v_A}{v_B}.$](https://latex.artofproblemsolving.com/5/5/d/55d05c8dc2057978b8598ff41595040760dfa071.png)
We know the formula for the trajectory of the point at the radius $2$ is $$\left(4\pi t\ -\ 2\sin\left(2\pi t\right),\ 2-\ 2\cos\left(2\pi t\right)\right)$$
$$\left(6\pi t\ -\ 3\sin\left(3\pi t\right),\ 2-3\cos\left(3\pi t\right)\right)$$