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

$ = {2\pi\cdot r \cdot dr \over dt}\cdot{dh \over dt}$


$ = 2\pi\cdot r \cdot{ dr \over dt}\cdot{dh \over dt}$

$\Delta r$ gets replaced with $dr$

