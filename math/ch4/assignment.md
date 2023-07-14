---
---
{% include MathJax %}

### Volume problem
      What is the volume of a cylinder?
      Area of base * height.

$$ a\cdot h $$

      So first what is the area of the base?

$$\pi\cdot r^2$$

      Volume is

$$\pi \cdot r(t)^2 \cdot h(t)$$


$$ {dh \over dt} $$

$$ {dr \over dt} $$


$${d\left(\pi \cdot r(t)^2   \cdot h(t)\right) \over dt } $$


$y = x$

$d(y) = d(x)$

${d(y)\over d(x)} = 1$

$V$ for volume

$r$ for radius

$h$ for height


$V = \pi \cdot r(t)^2 \cdot h(t)$

Apply $d$ to both sides of the equation.

$d(V) = d\left(\pi \cdot r(t)^2   \cdot h(t)\right)$

What's confusing us is treating r and h as functions of time.


$d(V) = d\left(\pi \cdot r^2   \cdot h\right)$

$d(u\cdot v) = d(u)\cdot v + u\cdot d(v)$

Apply $d$ to this $v = h$

$dv = dh$


Apply $d$ to $u = \pi \cdot r^2$

$du = 2\pi\cdot r \cdot dr$

Replace $u$ and $v$ with assigned values from above
$d(u\cdot v) = d(u)\cdot v + u\cdot d(v)$

$d(u\cdot v) = 2\pi\cdot r \cdot dr \cdot dh$

$d(V) = d(u\cdot v) = d\left(\pi \cdot r(t)^2   \cdot h(t)\right) = 2\pi\cdot r \cdot dr \cdot dh$

What we want is ${d(v) \over d(t)} = ?$

So divide previous equation by $d(t)$


${d(V) \over dt} = {d(u\cdot v) = d\left(\pi \cdot r(t)^2 \cdot h(t)\right)\over dt} = {2\pi\cdot r \cdot dr \cdot dh \over dt}$

What the word problem gives us is $\frac{d(r)}{d(t)}$ and $\frac{d(h)}{d(t)}$

$= {2\pi\cdot r \cdot dr \over dt}\cdot{dh \over dt}$


$= 2\pi\cdot r \cdot{ dr \over dt}\cdot{dh \over dt}$

$\Delta r$ gets replaced with $dr$


<hr>


## $x^2 + y^2 = 25$

$d(x^2 + y^2) = d(25)$

$2\cdot x \cdot dx + 2\cdot y \cdot dy = 0$

Apply $d$ operator again to find second derivative.

$d(2\cdot x \cdot dx + 2\cdot y \cdot dy) = d(0)$

$d(2\cdot x \cdot dx) + d(2\cdot y \cdot dy) = d(0)$

Aside, $dx$ is treated like a constant when inside $d()$.  So for example $d(2\cdot x) = 2\cdot d(x)$

Let's apply that idea $d(x\cdot dx) = d(x)\cdot dx$ 

Or in our case $d(2\cdot x\cdot dx) = 2\cdot d(x) \cdot dx$ end of aside.

$d(2\cdot x) \cdot dx + d(2\cdot y) \cdot dy = 0$

$2\cdot d(x) \cdot dx + 2\cdot d(y) \cdot dy = 0$

$2\cdot dx \cdot dx + 2\cdot dy \cdot dy = 0$

$2\cdot d^2x + 2\cdot d^2y = 0$

🖤

$f(x) = x^3-(\frac{3}{2})x^2-18x$

$\dot{f}(x)=3x^2-3x-18$

$\ddot{f}(x)=6x-3$

$\ddot{f}(3)=6(3)-3=15$

$\ddot{f}(-2)=6(-2)-3=-15$

🖤

$f(x) = x^3 - 4x^2 + x + 2$

$\dot{f}(x) = 3x^2 - 8x + 1$

$\ddot{f}(x) = 6x - 8$  

$\ddot{f}(x) = 2(3x - 4)$

$0 = 2(3(\frac{4}{3})-4)$

$\dot{f}(\frac{4}{3}) = 3(\frac{4}{3})^2 - 8(\frac{4}{3}) + 1$

$\dot{f}(\frac{4}{3}) = 3(\frac{16}{9}) - 8(\frac{4}{3}) + 1$

$\dot{f}(\frac{4}{3}) = 3(\frac{16}{9}) - 8(\frac{12}{9})$

$\dot{f}(\frac{4}{3}) = \frac{48}{9} - \frac{96}{9}$

$\dot{f}(\frac{4}{3}) = \frac{16}{3} - \frac{32}{3}$

$\dot{f}(\frac{4}{3}) = -\frac{16}{3}$

$x=\frac{--8 \pm \sqrt{8^2-(4)(3)(1)}}{2(3)}$

$x = \frac{8 \pm \sqrt{52}}{6}$

$x = \frac{8-\sqrt{52}}{6}$

$x = \frac{8+\sqrt{52}}{6}$

$x \approx 0.131 or 2.535$

$\dot{f}(x) = 3x^2 - 8x + 1$

$(x,\dot{f}(x))(0,1)(2,-3)(3,4)$

The first critical point is a maximum, and the second one is a minimum.

$f(x)$ is increasing over $-\infty < x < 0.131$ and $2.535 < x < \infty$. It decreasing over $0.131 < x < 2.535$.

$\ddot{f}(x) = 2(3x - 4)$

$0 = 2(3(\frac{4}{3})-4)$

$\frac{4}{3}$ is the inflection point.

201

It is decreasing over $-\infty < x < -2$ and $-1 < x < 2$.

It is increasing over  $-2 < x < -1$ and $2 < x < \infty$

227

$f(x) = x^{11} - 6x^{10}$

$\dot{f}(x) = 11x^{10} - 60x^{9}$

$\ddot{f}(x) = 110x^{9} - 540x^{8}$

$f(x) = x^{10}(x - 6)$

$\dot{f}(x) = x^9(11x - 60)$

$\ddot{f}(x) = x^8(110x - 540)$

$f(x)$ has zeros at $x = 0$ and  $x = 6$

$\dot{f}(x)$ has zeros at $x = 0$ and $x = \frac{60}{11}$ 

$\ddot{f}(x)$ has zeros at $x = 0$ and $x = \frac{540}{110}$

$f(x)$ is increasing over $(-\infty, 0)$ and $(\frac{60}{11}, \infty)$, and decreasing over $(0,\frac{60}{11})$

$f(x)$ has a local maximum at $x = 0$, and a local minimum at $x = \frac{60}{11}$

$\ddot{f}(x)$ has zeros at $x = 0$ and $x = \frac{540}{110}$

$f(x)$ is concave down over $(-\infty,\frac{540}{110})$, and concave up over $(\frac{540}{110},\infty)$  

$f(x)$ has an inflection point at $x = \frac{540}{110}$

231

$f(x)=\sin(\pi(x)) - \cos(\pi(x))$ over $[-1,1]$

🖤

Let $f(x) = -x^3 + 3x^2 - 6$. Find absolute max x value over $[-2,5]$

$\dot{f}(x) = -3x^2 + 6x$

$\dot{f}(x) = -3x(x - 2)$

$\dot{f}(x)$ has zeros at $x = 0$ and $x = 2$

$f(x)$ is increasing over $(0,2)$ and deacreasing over [-2,0) and (2,5]

$f(x)$ has a local minimum at $x = 0$, and a local maximum at $x = 2$

$f(-2)=-(-2)^3 + 3(-2)^2 - 6 = 14$

$f(1) = -(1)^3 + 3(1)^2 - 6 = -4$

$f(3) = -(3)^3 + 3(3)^2 - 6 = -6$

$f(3) = -(5)^3 + 3(5)^2 - 6 = -56$

$f(2) = -(2)^3 + 3(2)^2 - 6 = -2$

🖤

Let $g(x) = 2x^3 - 21x^2 + 60x$. Find the maximum value of g over [0,6].

$\dot{g}(x) = 6x^2 - 42x + 60$

$\dot{g}(x) = 6(x^2 - 7x + 10)$

$\dot{g}(x) = 6(x - 2)(x - 5)$

$\dot{g}(x)$ has zeros at $x = 2$ and $x = 5$

$f(x)$ is increasing over $[0,2) and (5,6]$. $f(x)$ is deacreasing over $(2,5)$

$f(x)$ has a local maximum at $x = 2$, and a local minimum at $x = 5$

$f(2) = 2(2)^3 - 21(2)^2 + 60(2) = 52$

$f(5) = 2(5)^3 - 21(5)^2 + 60(5) = 25$

$f(5) = 2(6)^3 - 21(6)^2 + 60(6) = 36$

