---
{"dg-publish":true,"dg-path":"Module 3/Unit 3 Formula Sheet - MOST DERIVATIVE STUFF.md","permalink":"/module-3/unit-3-formula-sheet-most-derivative-stuff/"}
---

## Unit 2 Review
### Continuity
A function $y=f(x)$ is continuous at an interior point $c$ of its domain if $\displaystyle\lim_{ x \to c } = f(c)$.
### [[School/2023-2024/AP Calculus/Basic Derivatives\|Definition of the derivative]]
$\displaystyle f'(x)=\lim_{ n \to 0 } \frac{f(x+h)-f(x)}{h}$
### [[School/2023-2024/AP Calculus/Module 3/3.1 - Alternate Definition of the Derivative\|Alternate definition of the derivative]]
$f'$ at the point $x=a$ is $\displaystyle\lim_{ x \to a } \frac{f(x)-f(a)}{x-a}$ (**provided the limit exists**).
### Differentiability
$y=f(x)$ is differentiable on $[a,b]$ if it has a derivative at every interior point of the interval and if the left and right handed limits are equal
### [[School/2023-2024/AP Calculus/Module 3/3.2 - Differentiability#Types of non-differentiability\|Types of non-differentiability]]
## New stuff
### Basic derivative rules
#### Derivative of a Constant Function
If $f$ is the function with constant value $c$, then $\displaystyle\frac{df}{dx}=\frac{d}{dx}(c)=0$.
#### Power rule for Positive and Negative Integer Powers of $x$
If $n$ is a positive integer, then $\displaystyle\frac{d}{dx}x^n=nx^{n-1}$ (this works for negative integer powers too)
#### Constant Multiple Rule
If $u$ is a differentiable function of $x$ and $c$ is a constant, then $\displaystyle\frac{d}{dx}(cu)=c\frac{du}{dx}$.
- For example, the derivative of $3x^4$ is $3$ times the derivative of $x^4$.
#### Sum and Difference Rule
$\displaystyle\frac{d}{dx}(u\pm v)=\frac{du}{dx}\pm \frac{dv}{dx}$
#### Product Rule
$\displaystyle\frac{d}{dx}(uv)=u\frac{dv}{dx}+v\frac{du}{dx}$.
#### Quotient Rule
At a point where $v\neq 0$, $\displaystyle\frac{d}{dx}\left( \frac{u}{v} \right)=\frac{v\frac{du}{dx}-u\frac{dv}{dx}}{v^2}$.
- If it helps, use the mnemonic “Low D High - High D Low”.
### Economics formulas
- **Average Cost:** $\displaystyle\frac{C(x)}{x}$
- **Average Increase in Cost:** $\displaystyle\frac{C(x+h)-C(x)}{h}$
- **Marginal Cost:** Estimates the cost of producing one unit beyond the present level of production – $\displaystyle\lim_{ h \to 0 }\left( \frac{C(x+h)-C(x)}{h} \right)$
- **“actual additional cost”:** $C(x + h) – C(x)$
- **Demand Function:** Expresses the relationship between unit price and the quantity demanded – $p = f(x)$
- **Revenue:** $R(x) = px$
- **Marginal Revenue:** $R'(x)$
	- Estimates the increase in revenue that will result from selling one additional unit
	- **“actual additional revenue made”** $R(x + h) – R(x)$
- **Profit**: $P(x) = R(x) – C(x)$
- **Marginal Profit:** Measures the rate of change of the profit function P and provides us with a good approximation of the actual profit or loss realized from the sale of 1 more unit of an item sold – $P x'()$
	- **“actual gain in profit”**: $P(x + h) – P(x)$
### Particle motion formulas
- **Velocity:** first derivative of speed. 
	- The particle stops when $v=0$.
	- The particle is moving right (or up) if the velocity is positive. The particle is moving left (or down) if the velocity is negative.
	- A particle is speeding up if the signs of velocity and acceleration are the same sign. A particle is slowing down if the signs of velocity and acceleration are opposite signs.
- **Acceleration:** second derivative of speed (or first derivative of velocity).
- **Average acceleration**
	- Equal to $\frac{\Delta v}{\Delta t}$ or change in velocity/change in time.
- **Average velocity**: displacement/travel time.
- **Speed:** this is just the absolute value of velocity.
- **Displacement** is the change in position (final position - starting position).
### Trig derivatives
$\displaystyle\frac{d}{dx}\sin x=\cos x$

$\displaystyle\frac{d}{dx}\cos  x=-\sin x$

$\displaystyle\frac{d}{dx}\tan x=\sec^2 x$

$\displaystyle\frac{d}{dx}\cot x=-\csc^2 x$

$\displaystyle\frac{d}{dx}\sec x=\sec x\tan x$

$\displaystyle\frac{d}{dx}\csc x=-\csc x \cot x$
### The chain rule
If $f$ is differentiable at the point $u=g(x)$, and $g$ is differentiable at 
$x$, then the composite function $(f\circ g)(x)= f(g(x))$ is differentiable at $x$, and $(f\circ g)'(x)=f'(g(x))\cdot g'(x)$.
### [[School/2023-2024/AP Calculus/Module 3/3.7 - Implicit Differentiation\|Implicit Differentiation]]
- Basically, just chain $y$ with its derivative with respect to $x$, which is $\displaystyle\frac{dy}{dx}$, whenever you see it.
### Inverse trig derivatives
You can just derive these, so don’t put too much effort into memorizing them.
- The derivative of arcsin x is $\displaystyle d/dx(\arcsin x) = 1/\sqrt{ 1-x² }$, when $-1 < x < 1$
- The derivative of arccos x is $\displaystyle d/dx(\arccos x) = -1/\sqrt{1-x²  }$, when $-1 < x < 1$
- The derivative of arctan x is $\displaystyle d/dx(\arctan x) = 1/(1+x²)$, for all $x$ in $R$
- The derivative of arccsc x is $\displaystyle d/dx(csc^{-1} x) = -1/(|x|\sqrt{x²-1  })$, when $x < -1$ or $x > 1$
- The derivative of arcsec x is $\displaystyle d/dx(sec^{-1} x) = 1/(|x|\sqrt{x²-1  }$), when $x < -1$ or $x > 1$
- The derivative of arccot x is $\displaystyle d/dx(cot^{-1} x) = -1/(1+x²)$, for all $x$ in $R$
### Exponent and log formulas
#### Derivative of $e^x$
- The derivative of $e^x$ is simply $e^x$.
#### Derivative of any general $e^u$
$\displaystyle\frac{d}{dx}(e^u)=e^u\left( \frac{du}{dx} \right)$
#### Derivative of any general $a^u$
$\displaystyle\frac{d}{dx}(a^u)=a^u\ln a\left( \frac{du}{dx} \right)$
#### Derivative of $\ln x$
- Simply $\displaystyle\frac{1}{x}$.
#### Derivative of any general $\ln u$
$\displaystyle\frac{d}{dx}(\ln u)=\frac{1}{u}\left( \frac{du}{dx} \right)$
#### Derivative of $\log_{a}x$
$\log_{a}x$ is $\displaystyle\frac{1}{x\ln a}$.
#### Any general $\log_{a}u$
$\displaystyle\frac{d}{dx}(\log_{a}u)=\frac{1}{u\ln a}\left( \frac{du}{dx} \right)$
