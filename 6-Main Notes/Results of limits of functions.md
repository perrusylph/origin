2025-07-20 16:01

Tags: [[math]], [[3- Tags/calculus]]

Before, remember any function $f: \mathbb{R} \rightarrow \mathbb{R}$ can be expressed as the sum of an even function ($P(x)$) and an odd function ($I(x)$). This means
$$
f(x) = P(x) + I(x)
$$
for all $x \in \mathbb{R}$, where $P(x)$ and $I(x)$ are unique and are:
$$
P(x) = \frac{f(x) + f(-x)}{2} \quad I(x) = \frac{f(x)-f(-x)}{2}
$$
# Single-variable

## Criterion of sequences for limits

Let $A \subset \mathbb{R}, f : A \rightarrow \mathbb{R}$ and $x_{0}$ be an accumulation point of $A$. The next statements are equivalent:
1. $\lim_{ x \to x_{0} } f(x) = L.$
2. For every sequence $\{ a_{n} \}$ in $A$ that converges to $x_{0}$ such that $a_{n} \neq x_{0}$ for all $n \in \mathbb{N}$, the sequence $\{ f(a_{n}) \}$ converges to $L$.
## Operations on limits of functions

Let $f : A \rightarrow \mathbb{R}$ and $g : A \rightarrow \mathbb{R}$ be two functions and let $c$ be a real number. If
$$
\lim_{ x \to x_{0} } f(x) = L \quad \text{ and } \quad \lim_{ x \to x_{0} } g(x) = M 
$$
Then
1. $\lim_{ x \to x_{0} } c \cdot f(x) = c  L.$
2. $\lim_{ x \to x_{0} } f(x) + g(x) = L + M.$
3. $\lim_{ x \to x_{0} } f(x) - g(x) = L - M.$
4. $\lim_{ x \to x_{0} } f(x) \cdot g(x) = L \cdot M.$
5. If, in addition, $M \neq 0$, then
$$
\lim_{ x \to x_{0} } \frac{f(x)}{g(x)} = \frac{L}{M}.
$$
## Squeeze theorem on functions

Set $f,g,h: A \rightarrow \mathbb{R}$ and set $x_{0} \in A$. If 
$$
f(x) \leq g(x) \leq h(x), \text{ for all x} \in A, x\neq x_{0}
$$
and if 
$$
\lim_{ x \to x_{0} } f(x) = L = \lim_{ x \to x_{0} } h(x)  
$$
then
$$
\lim_{ x \to x_{0} } g(x) = L. 
$$
- If $\lim_{ x \to x_{0} } f(x) = L, \text{ then } \lim_{ x \to x_{0} } |f(x)| = |L|.$

# References
