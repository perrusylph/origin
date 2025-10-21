2025-07-19 12:23
Tags: [[math]],[[3- Tags/calculus]]
## Properties of numbers

![[Pasted image 20250719122203.png]]
![[Pasted image 20250719122618.png]]
__Note:___ $P$ is the set of positive numbers (numbers $a$ such that $a > 0$).
## Order results

![[Pasted image 20250719123031.png]]

- If $a<b$ and $b<c$, then $a<c$.
- If $a,b >0$ then $ab >0$.
- If $a<0$ and $b<0$, then $ab>0$. As a consequence, for every $a \neq 0$, $a{^2}>0$.
- If $a > 0, b<0$ then $ab<0$.
- If $a<0, b>0$ then $ab<0$.

# Other results

For $a,b \in \mathbb{R}$ it follows:
1. $a \cdot 0 = 0$
2. $-a = (-1)(a)$
3. $-(-a) = a$
4. $(-a)(b) = -(ab)$
5. $(-a)(-b) = ab$

## Triangle inequality

For all numbers $a$ and $b$, we have 
$$
|a+b| \leq |a| + |b|
$$
- $|a| =\sqrt{ a{^2} }$. Aquí $\sqrt{ x }$ denota la raíz cuadrada positiva de $x$.

### Consequences of triangle inequality

Set $a,b \in \mathbb{R}$. The next inequalities are achieved:

1. $|a-b| \leq |a| + |b|$
2. $|a|-|b| \leq |a-b|$ (Desigualdad del triángulo inversa)
3. $|b|-|a| \leq |a-b|$

## Important absolute value results

- For every $a \in \mathbb{R}, a \leq |a|$ and $-a \leq |a|$.
- Let us consider $a, x \in \mathbb{R}$ with $a \geq 0$.
1. 
$$
\begin{align}
|x| \leq a & \iff -a \leq x \text{ and } x \leq a \\
& \iff x \in [-a,a]. 
\end{align}
$$
2. 
$$
\begin{align}
|x| \geq a  & \iff -a \geq x \text{ or } x \geq a \\
 & \iff x \in (-\infty,-a] \cup [a,\infty). 
\end{align}
$$

## Square results 

Set $x,y \in \mathbb{R}$ such that $x,y \geq 0$. We define the square root of $x$ as follows:
$$
\sqrt{ x } = y \iff x = y^{2}.
$$
- For $x>0$ these inequalities hold:
$$
-\sqrt{ x } \leq 0, \sqrt{ x } \geq 0.
$$
- For $y \in \mathbb{R}$ we have that $\sqrt{ y^{2} } = |y|$.
- $|y^{2}| = y^{2}$.
- $|y^{2}| = |y|^{2}$.
- For $x,y \in \mathbb{R}$ where $x,y \geq 0$.
$$
x \leq y \iff x^{2} \leq y^{2}
$$
- For $x,y \in \mathbb{R}$ where $x,y \geq 0$.
$$
 x \leq y \iff \sqrt{ x } \leq \sqrt{ y }
$$
## Triangle inequality for arbitrarily many terms 

For any finite set of numbers $x_{1},x_{2},\dots,x_{n} \in \mathbb{R}$ we have 
$$
|x_{1}+\dots+x_{n}| \leq |x_{1}|+\dots+|x_{n}|.
$$
And the equality happens when iff all $x_{i}$ have the same sign.

## Cauchy-Schwarz inequality

Let $a_{1},a_{2},\dots,a_{n}$ and $b_{1},b_{2},\dots,b_{n}$ arbitrary real numbers. Then
$$
|A \cdot B| = \left|\sum_{1=i}^{n} a_{i}b_{i} \right| \leq \left( \sum_{i=1}^{n} a_{i}^{2} \right)^{1/2} \left( \sum_{i=1}^{n}b_{i}^{2} \right)^{1/2} = |A||B|
$$
# Product related results

1. Set $a,b \in \mathbb{R}$. If $ab = 0 \implies a=0 \text{ or } b = 0$.
2. Set $a \in \mathbb{R}, a \neq 0$. Si $ax = a$, entonces $x=1$.
3. Set $a,b,c \in \mathbb{R}$ with $a \neq 0$. If $ab = ac \implies b = c$.

# Notable products

Notation: We define $x-y := x+(-y)$.

For $x,y \in \mathbb{R}$ the next follows:

1. Difference of squares: $x^{2} - y^{2} = (x-y)(x+y)$.
2. If $x^{2} = y^{2}$ then $x=y$ or $x = -y$.
3. Difference of cubes: $x^{3} - y^{3} = (x-y) (x^{2} + xy + y^{2})$.
4. Addition of cubes: $x^{3} + y^{3} = (x-y) (x^{2}- xy + y^{2})$.

# Multiplicative inverse related results

Notation: If $a \in \mathbb{R}$, then $a^{-1} = \frac{1}{a}$. We define $\frac{a}{b} := a \cdot b^{-1}$.

For $a,b,c,d \in \mathbb{R}$ the next follows:

1. For $a,b \neq 0$,
$$
(ab)^{-1} = a^{-1} b^{-1}
$$
2. For $b,c \neq 0$,
$$
\frac{a}{b} = \frac{ac}{bc}
$$
3. For $b,d \neq 0$,
$$
\frac{a}{b} + \frac{c}{d} = \frac{ad+bc}{bd}
$$
4. For $b,d \neq 0$,
$$
\frac{a}{b} \cdot \frac{c}{d} = \frac{ac}{bd}
$$
5. For $b,c,d \neq 0$,
$$
\frac{\frac{a}{b}}{\frac{c}{d}} = \frac{ad}{bc}
$$
6. For $b,d \neq 0$,
$$
\frac{a}{b} = \frac{c}{d} \implies ad = bc
$$
## Bounded set equivalence

These definitions are equivalent:
1. $\exists m,M \in \mathbb{R} : \forall a \in A, m \leq a \leq M.$
2. $\exists M \in \mathbb{R} : \forall a \in A,  |a| \leq M.$

Note: Remember the supremum is the lowest upper bound and the infimum is the highest lower bound.
## Axiom of Supremum

If $A \subseteq \mathbb{R}$ is non-empty and $A$ is bounded from above then there is $\alpha \in \mathbb{R}$ such that:
$$
\alpha = sup(A)
$$
## Results of suprema and infima

- Let $A \subseteq \mathbb{R}$ with $A \neq \emptyset$ and bounded. The supremum and infimum of $A$ are unique.
- Let $A, B \subseteq \mathbb{R}$ non-empty sets. If it holds that for all $a \in A$ and for all $b \in B$ $a \leq b \implies sup(A) \leq inf(B)$.
- Let $C \subseteq A \subseteq \mathbb{R}$ where $C$ is non-empty and $A$ is bounded. It follows that:
$$
inf(A) \leq inf(C) \leq sup(C) \leq sup(A).
$$
- Let $A' \subseteq A \subseteq R$ and $B' \subseteq B \subseteq \mathbb{R}$ where $A',B'$ are non-empty. If it follows that:
1. $\forall a \in A, \forall b \in B (a \leq b)$
2. $sup(A') = inf (B')$
$\implies sup (A) = inf(B)$
# References

[[2- Source Material/Books/Math Books/Calculus]]
[Nekomath](blog.nekomath.com)


