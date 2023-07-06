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

$(x,\dot{f}(x))(0,1)(1,-4)(2,-3)(3,4)$

