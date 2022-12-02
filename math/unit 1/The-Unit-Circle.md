---
layout: default
title: Unit Circle
nav_order: 2
parent: Unit 1
grand_parent: math
---
### What is the Unit Circle
* The Unit Circle is a circle with a radius of 1. This circle allows us to find the trigonometric functions of an angle without a calculator. Below is a picture of the unit circle[^1]
```desmos-graph
top=1.2; bottom=-1.2;
left=-1.75; right=1.75;
---
y=x|-0.707<x<0.707|black
y=-x|-0.707<x<0.707|black

x=0|-1<y<1|black
y=0|-1<x<1|black

y=\sqrt{3}x|-0.866<y<0.866|black
y=-\sqrt{3}x|-0.866<y<0.866|black

y=0.5x|-0.4472<y<0.4472|black
y=-0.5x|-0.4472<y<0.4472|black

x^2+y^2=1|blue

(1,0)|open|blue|label:(1,0)
(\frac{\sqrt{3}}{2},\frac{1}{2})|open|blue|label:((√3)/2,1/2)
(\frac{\sqrt{2}}{2},\frac{\sqrt{2}}{2})|open|blue|label:((√2)/2,(√2)/2)
(0.5,\frac{\sqrt{3}}{2})|open|blue|label:(1/2,(√3)/2)
(0,1)|open|blue|label:(0,1)
(-\frac{\sqrt{3}}{2},\frac{1}{2})|open|blue|label:((-√3)/2,1/2)
(-\frac{\sqrt{2}}{2},\frac{\sqrt{2}}{2})|open|blue|label:((-√2)/2,(√2)/2)
(-0.5,\frac{\sqrt{3}}{2})|open|blue|label:(-1/2,(√3)/2)
(-1,0)|open|blue|label:(-1,0)
(-\frac{\sqrt{3}}{2},-\frac{1}{2})|open|blue|label:((-√3)/2,1-/2)
(-\frac{\sqrt{2}}{2},-\frac{\sqrt{2}}{2})|open|blue|label:((-√2)/2,(-√2)/2)
(-0.5,-\frac{\sqrt{3}}{2})|open|blue|label:(-1/2,(-√3)/2)
(0,-1)|open|blue|label:(0,-1)
(\frac{\sqrt{3}}{2},-\frac{1}{2})|open|blue|label:((√3)/2,1/2)
(\frac{\sqrt{2}}{2},-\frac{\sqrt{2}}{2})|open|blue|label:((√2)/2,(√2)/2)
(0.5,-\frac{\sqrt{3}}{2})|open|blue|label:(1/2,(√3)/2)

(1,0)|open|blue|label:0 or π, 0° or 360°
(\frac{\sqrt{3}}{2},\frac{1}{2})|open|blue|label:π/6, 30°
(\frac{\sqrt{2}}{2},\frac{\sqrt{2}}{2})|open|blue|label:π/4, 45°
(0.5,\frac{\sqrt{3}}{2})|open|blue|label:π/3, 60°
(0,1)|open|blue|label:π/2, 90°
(-\frac{\sqrt{3}}{2},\frac{1}{2})|open|blue|label:2π/3, 120°
(-\frac{\sqrt{2}}{2},\frac{\sqrt{2}}{2})|open|blue|label:3π/4, 135°
(-0.5,\frac{\sqrt{3}}{2})|open|blue|label:5π/6, 150°
(-1,0)|open|blue|label:π, 180°
(-\frac{\sqrt{3}}{2},-\frac{1}{2})|open|blue|label:7π/6, 210°
(-\frac{\sqrt{2}}{2},-\frac{\sqrt{2}}{2})|open|blue|label:5π/4, 225°
(-0.5,-\frac{\sqrt{3}}{2})|open|blue|label:4π/3, 240°
(0,-1)|open|blue|label:3π/2, 270°
(\frac{\sqrt{3}}{2},-\frac{1}{2})|open|blue|label:5π/3, 300°
(\frac{\sqrt{2}}{2},-\frac{\sqrt{2}}{2})|open|blue|label:7π/4, 315°
(0.5,-\frac{\sqrt{3}}{2})|open|blue|label:11π/6, 330°
```
* Each of these points on the circle corresponds to a different angle.
---
### Using the Unit Circle
* You can use the unit circle to find the value of trigonometric functions by simply using the points on the circle that correspond to the angle you are trying to find. The table below shows how to use the points.
|name|abbreviation|trig ratio|how to find it using the unit circle|
|---|---|---|---|
|cosine|$\cos{\theta}$|$\frac{Adjacent}{Hypotenuse}$|$x\ coordinate$|
|sine|$\sin{\theta}$|$\frac{Opposite}{Hypotenuse}$|$y\ coordinate$|
|tangent|$\tan{\theta}$|$\frac{Opposite}{Adjacent}$|$\frac{y\ coordinate}{x\ coordinate}$|
* This is relatively self explanatory. You can find the value of the trigonometric ratio by taking the x coordinate for $\cos$, the y coordinate for $\sin$ and divide the y coordinate by the x coordinate for $\tan$.
---
### New Trigonometric functions
* We will now introduce new trigonometric functions. These functions are essentially reciprocals[^2]of the main three trigonometric functions. A table similar to the one below will be used.
|name|abbreviation|Reciprocal|trig ratio|how to find it using the unit circle|
|---|---|---|---|---|
|secant|$\sec{\theta}$|$\frac{1}{\cos{\theta}}$|$\frac{Hypotenuse}{Adjacent}$|$\frac{1}{x\ coordinate}$|
|cosecant|$\csc{\theta}$|$\frac{1}{\csc{\theta}}$|$\frac{Hypotenuse}{Opposite}$|$\frac{1}{y\ coordinate}$|
|cotangent|$\cot{\theta}$|$\frac{1}{\tan{\theta}}$|$\frac{Adjacent}{Opposite}$|$\frac{x\ coordinate}{y\ coordinate}$|
* This table is also relatively self explanatory. You can find the value of the trigonometric ratio by calculating $\frac{1}{x\ coordinate}$ of the point corresponding to the angle for $\sec$, $\frac{1}{x\ coordinate}$ of the point corresponding to the angle for $\csc$, and $\frac{x\ coordinate}{y\ coordinate}$ for $\cot$.
---
### Signs in each coordinate
|Trig Ratio|Quadrant I|Quadrant II|Quadrant III|Quadrant IV|
|---|---|---|---|---|
|$\sin{\theta}$,<br>$\csc{\theta}$|+|+|-|-|
|$\cos{\theta}$,<br>$\sec{\theta}$|+|-|-|+|
|$\tan{\theta}$,<br>$\cot{\theta}$|+|-|+|-|
* As you can see, all of the trigonometric functions are positive in the 1<sup>st</sup> coordinate, which is an important characteristic of these functions.
* A mnemonic to memorize this (credit Ms. Denbesten) is "all students take calculus"[^3]. You can use this mnemonic to create a matrix like $\begin{array}{c|c}a&s \\ \hline t&c\end{array}$ . The letters of these correspond to all, sine, tan, and cosine, and their positions correspond to the quadrant they are in.
---
[^1]: I apologize for the strange labels, its a side effect of the extension I am using to create these graphs. In the future, this is the notation I will use for these labels
[^2]: The function is a reciprocal, but it is NOT an inverse. Those will be covered later in the unit.
[^3]: The mnemonic isn't entirely true, but its still a good mnemonic imo