---
{"dg-publish":true,"dg-path":"U-Substitution for Integration.md","permalink":"/u-substitution-for-integration/","created":"","updated":""}
---

#calc/concept 
When we need to take the antiderivative of a function that would require the [[School/AP Calculus/Module 3/3.6 - The Chain Rule\|Chain Rule]] to derive, we need to use the technique of **u-substitution**.
## Steps to perform u-sub
1. Check to see if your problem can be simplified in some way. For example, a lot of trig functions can be simplified, which makes your life a lot easier.
2. Pick a part of the function to substitute (to call $u$). Often, you will want to pick a more complicated part.
3. Take the derivative of $u$ with respect to $x$. 
4. Isolate $dx$.
5. Substitute $dx$ for your other side of the equation. 
6. Pull out constants, antidifferentiate, and put your $x$ back in.
7. If this doesn’t work, go back and choose a different $u$.
It’s not possible to know right off the bat which $u$ will work, so you may end up having to try a couple different values of $u$.
## Example
**Q**: Solve $\int  \sqrt{ 2x+1 }\, dx$.
**A**:
1. This problem is as simplified as we can get it.
2. We let our $u$ be $2x+1$.
3. This means that $du=2dx$.
4. Isolating $dx$, we find that $dx=\frac{1}{2}du$.
5. We plug in what we found to be equal to $dx$ into the original equation and also plug our $u$ in: $\int \frac{1}{2}\sqrt{ u } \, du$
6. We can solve this using our rules ([[School/AP Calculus/Module 6/6.2 - Antidifferentiation by Subsitution\|here]]): $\displaystyle\frac{1}{2}\left( \frac{k^{3/2}}{\frac{3}{2}} +c\right)$, which becomes $\frac{1}{3}(k^{3/2}+c)$. Plugging $x$ back in (remember that $2x+1=u$), we get $\frac{1}{3}((2x+1)^{3/2}+c)$, which is our final answer.