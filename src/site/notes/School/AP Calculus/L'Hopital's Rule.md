---
{"dg-publish":true,"dg-path":"L'Hopital's Rule.md","permalink":"/l-hopital-s-rule/"}
---

#calc/theorem 
- A technique used to evaluate limits that take indeterminate forms: $0/0$ or $∞/∞$.
## Statement
The rule states that for for functions $f$ and $g$ where $\displaystyle\lim_{ x \to a } \frac{f(x)}{g(x)}=\frac{0}{0}$ or $\frac{\infty}{\infty}$, $\displaystyle\lim_{ x \to a } \frac{f(x)}{g(x)}=\lim_{ x \to a } \frac{f'(x)}{g'(x)}$.
- Essentially, if it’s an indeterminate limit, derive the top and bottom.
- Make sure $f(x)$ and $g(x)$ are differentiable and the new limit exists
## Examples
1. $\displaystyle\lim_{ x \to 0 } \frac{\sin x}{x}=\lim_{ x \to 0 } \frac{\cos x}{1}=1$
2. $\displaystyle\lim_{ x \to \infty } \frac{x}{e^x}=\lim_{ x \to \infty } \frac{1}{e^x}=0$