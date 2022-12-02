---
layout: default
title: General Area Formula
nav_order: 1
parent: Unit 3
grand_parent: math
---
# Law of Cosines
The law of cosines is a method to find either an unincluded side in any SAS triangle or a missing angle in any SSS triangle
## Derivation
We need a triangle to do this derivation. Below you see a general triangle with side-lengths a, b, c, and angles A, B, C. The purpose of the proof is to find the length of side length $\overrightarrow{CB}$. We can do this by finding the coordinates of B and C, and then using the distance formula.
$$B = (c, 0)\\
C = (b\cos{A}, b\sin{A})\\
\overrightarrow{CB}=a\\
\therefore a^2=(b\cos{A}-c)^2+(b\sin{A}-0)^2$$
Expanding this out, we get
$$a=b^2\cos^2{A}-2bc\cos{A}+c^2+b^2sin^2{A}$$
Using this, we can factor by $b^2$ and use the pythagorean trig identity[^1]. 
$$a=b^2(\cos^2{A}+\sin^2{a})-2bc\cos{A}+c^2\\
a^2=b^2(1)-2bc\cos{A}+c^2\\
a^2=b^2+c^2-2bc\cos{A}$$
## Using the Law of Cosines
We can use the law of cosines to find a missing side, by simply plugging in the corresponding sides and the corresponding angle. This approach can only be used to find the missing side in an SAS triangle.<br>
We can also use the law of cosines in more than one way to find the angle in an SSS triangle. We can rearrange the equation as
$$A=\arccos{\frac{a^2-b^2-c^2}{-2bc}}$$
so that we can solve for angle A. In this equation, a is the side of the angle that you are solving for, and b and c are the other two included angles. If you notice in the equation, it is essentially a quadratic equation, meaning you can use the equatric formula. This is excellent for the ambigious case which will be covered later.
## The Ambigious case
#### What you may have seen is that sometimes, you can use the Law of Cosines on SSA triangles. This is a tricky task, however, because it can create the ambigious case. The ambigious case is when there are two possible triangles for the quantities given. If you wish to solve for the unincluded side in a AAS, you need to use the quadratic formula. For example, if you are solving for b given a and c,
$$a^2=b^2+c^2-2bc\cos{A}$$
#### If we define a quadratic in the form $y=a^2x+bx+c$, we can use the quadratic formula on this, where $c^2-a^2$ is the value for c, $-2c\cos{A}$ is the b value, and 1 is the a value because $b^2$ has no coefficient. You can simply plug in these values into the equation and get the two answers for the side we are solving for. Normally, you can take these two answers and narrow down the one that makes the most sense, but sometimes you will have to accept two differnent possible answers.
---
[^1]: This will be covered in depth next unit.