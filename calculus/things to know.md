---
layout: default
title: Home
nav_order: 1
---

# Things to Know - Calculus Edition
A list of things to memorize before the exam

note: does not contain methods or things that can't be easily written out. Really just formulas and theorems.

* squeeze theorem
    * if $h(x)\leq f(x)\leq g(x)$ for all x in an open interval near some point a
    * and $\displaystyle\lim_{x\to a}h(x)=\lim_{x\to a}g(x)=L$,
    * then $\displaystyle\lim_{x\to a}f(x)=L$

* A function is continuous if the following are true:
    * $f(a)$ is defined
    * $\displaystyle\lim_{x\to a}f(x)$ exists
    * $\displaystyle\lim_{x\to a}f(x) = f(x)$

* Intermediate Value Theorem (IVT)
    * if $f(x)$ is continuous on the closed interval $[a,b]$,
    * and $k$ is any number between $f(a)$ and $f(b)$,
    * then there is at least one number $c$ in the interval $[a,b]$ such that $f(c)=k$

* $\displaystyle\lim_{x\to\infty}\frac{1}{x^r}$

* $\displaystyle\lim_{\theta\to0}\frac{\sin k\theta}{k\theta}=1$

* $\displaystyle\lim_{\theta\to0}\frac{1-\cos k\theta}{k\theta}=0$

* Definition of the derivative...
    * At any point:
        * $\displaystyle\lim_{h\to0}\frac{f(x+h)-f(x)}{h}$
    * At a specfic point:
        * $\displaystyle\lim_{x\to a}\frac{f(x)-f(a)}{x-a}$

* How might $f'(x)$ fail to exist?
    * If the function has a corner
    * If the function has a cusp
    * If the function has a vertical tangent
    * If the function has a discontinuity

* $\frac{d}{dx}\big(cx^n\big)=cnx^{n-1}$
* $\frac{d}{dx}\big(u\pm v)=u'\pm v'$
* $\frac{d}{dx}\big(e^x\big)=e^x$
* $\frac{d}{dx}\big(f(x)g(x)\big)=f(x)g'(x)+f'(x)g(x)$
* $\frac{d}{dx}\Big(\frac{f(x)}{g(x)}\Big)=\frac{g(x)f'(x)-f(x)g'(x)}{g(x)^2}$
* $\frac{d}{dx}\big(\sin x\big)=\cos x$
* $\frac{d}{dx}\big(\cos x\big)=-\sin x$
* $\frac{d}{dx}\big(\tan x\big)=\sec^2x$
* $\frac{d}{dx}\big(\sec x\big)=\sec x\tan x$
* $\frac{d}{dx}\big(\csc x\big)=-\csc x\cot x$
* $\frac{d}{dx}\big(\cot x\big)=-\csc^2x$
* $\frac{d}{dx}\big(f(g(x))\big)=f'(g(x))g'(x)$

* Derivatives of inverses
    * if $f$ is a function that is differentiable on some interval and $g$ is its inverse
    * then, $g'(x)=\frac{1}{f'(g(x))}$

* $\frac{d}{dx}\big(\arcsin u\big) = \frac{du}{\sqrt{1-u^2}}$
* $\frac{d}{dx}\big(\arccos u\big) = -\frac{du}{\sqrt{1-u^2}}$
* $\frac{d}{dx}\big(\arctan u\big) = \frac{1}{1+u^2}$
* $\frac{d}{dx}\big(arccot\ u\big) = -\frac{du}{1+u^2}$
* $\frac{d}{dx}\big(arcsec\ u\big) = \frac{du}{|u|\sqrt{u^2-1}}$
* $\frac{d}{dx}\big(arccsc\ u\big) = -\frac{du}{|u|\sqrt{u^2-1}}$
* $\frac{d}{dx}\big(a^u\big)=a^u\ln a\frac{du}{dx}$
* $\frac{d}{dx}\big(\ln u\big)=\frac{u'}{u}$
* $\frac{d}{dx}\log_au=\frac{u'}{u\ln a}$

* Extreme Value Theorem
    * If $f$ is continuous on a close interval $[a,b]$
    * then $f$ has a maximum and minimum value on the interval

* Fermat's Theorem
    * If a function, $f(x)$, has a local maximum or minimum value at an interior point $c$ of its domain
    * and $f'(c)$ exists
    * then $f'(x)=0$

* Rolle's Theorem
    * If some function $f$ is continuous on $[a,b]$,
    * and differentiable on $(a,b)$,
    * and $f(a)=f(b)$
    * then there exists at least one number $c$ in $(a,b)$ such that $f'(c)=0$

* Mean Value Theorem (MVT)
    * If $f$ is continuous on $[a,b]$
    * and differentiable on $(a,b)$
    * then there exists some point $c$ in the interval such that 
    * $f'(c)=\frac{f(b)-f(a)}{b-a}$

* First Derivative Test
    * A Local Minimum occurs at any critical point where the derivative changes from negative to positive
    * A Local Maximum occurs at any critical point where the derivative changes from positive to negative
    * if $f'(x)$ does not change sign at a critical point, then it has neither

* Second Derivative Test
    * If $f'(c)=0$ and $f''(c)>0$, then $f$ has a local minimum at $c$
    * If $f'(c)=0$ and $f''(c)<0$, then $f$ has a local maximum at c
    * If $f'(c)=0$ and $f''(c)=0$, then the test is inconclusive

* L'Hospital's Rule
    * $f$ and $g$ are differentiable functions on $(a,b)$
    * that contains a point $c$
    * and $g'(x)\neq0$ for all $x$ in $(a,b)$.
    * If $\displaystyle\lim_{x\to c}\frac{f(x)}{g(x)}$ produces an indeterminate form of type $\frac{0}{0}$ or $\frac{\infty}{\infty}$,
    * then $\displaystyle\lim_{x\to c}\frac{f(x)}{g(x)}=\lim_{x\to c}\frac{f'(x)}{g'(x)}$

* Trapezoidal Rule (TRAM)
    * $TRAM=\frac{1}{2}\big(\frac{b-a}{n}\big)\big(f(x_0)+2f(x_1)+2f(x_2)+\dots+f(x_n)\big)$

* $\int x^ndx=\frac{x^{n+1}}{n+1}+C$
* $\int\frac{1}{x}dx=\ln|x|+C$
* $\int e^xdx=e^x+C$
* $\int\sin xdx=-\cos x+C$
* $\int\cos xdx=\sin x+C$
* $\int\sec^2xdx=\tan x+C$
* $\int\csc^2xdx=-\cot x+C$
* $\int\sec x\tan xdx=\sec x+C$
* $\int\csc x\cot xdx=-\csc x+C$