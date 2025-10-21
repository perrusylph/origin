[[math]], [[calculus]]
## Divergence test

If $\lim_{ n \to \infty } a_{n} \neq 0$ then $\sum a_{n}$ diverges.

## Facts (Absolute convergence)

1. If $\sum a_{n}$ is absolutely convergent and its value is $s$ then any rearrangement of $\sum a_{n}$ will also have a value of $s$.
2. If $\sum a_{n}$ is conditionally convergent and $r$ is any real number then there is a rearrangement of $\sum a_{n}$ whose value will be $r$.

## Geometric series

Written in the form:
$$
\sum_{n=1}^{\infty} ar^{n-1} \text{ or, equivalently } \sum_{n=0}^{\infty} ar^{n}
$$
It can be proven that its partial sums are,
$$
s_{n} = \frac{a(1-r^{n})}{1-r} = \frac{a}{1-r} - \frac{ar^{n}}{1-r}
$$
Taking limit on the partial sums we find,
$$
\lim_{ n \to \infty } s_{n} = \lim_{ n \to \infty } \left( \frac{a}{1-r} - \frac{ar^{n}}{1-r} \right) = \lim_{ n \to \infty } \frac{a}{1-r} - \lim_{ n \to \infty } \frac{ar^{n}}{1-r} = \frac{a}{1-r} - \frac{a}{1-r} \lim_{ n \to \infty } r^{n}
$$
The limit above will exist only when $-1 < r \leq 1$. However, note that if $r = 1$ we would be dividing by zero. Therefore, the limit will exist and be finite provided $-1<r<1$ and in this case the limit is zero and so we get,
$$
\lim_{ n \to \infty } s_{n} = \frac{a}{1-r} 
$$
Therefore, a geometric series will converge if $-1<r<1$, which is written $|r|<1$, its value is,
$$
\sum_{n=1}^{\infty}ar^{n-1} = \sum_{n=0}^{\infty}ar^{n} = \frac{a}{1-r}
$$
## Integral test

Suppose that $f(x)$ is a continuous, positive and decreasing function on the interval $[k,\infty)$ and that $f(n) = a_{n}$ then,
1. If $\int_{k}^{\infty} f(x) dx$ is convergent so is $\sum_{n=k}^{\infty} a_{n}$.
2. If $\int_{k}^{\infty} f(x) dx$ is divergent so is $\sum_{n=k}^{\infty} a_{n}$.
## Fact (The $p$-series test)

If $k >0$ then $\sum_{n=k}^{\infty} \frac{1}{n^{p}}$ converges if $p>1$ and diverges if $p\leq 1$.

## Comparison test

Suppose that we have two series $\sum a_{n}$ and $\sum b_{n}$ with $a_{n}, b_{n} \geq 0$ for all $n$ and $a_{n} \leq b_{n}$ for all $n$. Then,

1. If $\sum b_{n}$ is convergent so is $\sum a_{n}$.
2. If $\sum a_{n}$ is divergent so is $\sum b_{n}$.

## Limit comparison test

Suppose that we have two series $\sum a_{n}$ and $\sum b_{n}$ with $a_{n}\geq 0, b_{n} > 0$ for all $n$. Define,
$$
c = \lim_{ n \to \infty } \frac{a_{n}}{b_{n}}
$$
If $c$ is positive and finite then either both series converge or both series diverge.

## Alternating series test

Suppose that we have a series $\sum a_{n}$ and either $a_{n} = (-1)^{n}b_{n}$ or $a_{n} = (-1)^{n+1} b_{n}$ where $b_{n}\geq 0$ for all $n$. Then if,

1. $\lim_{ n \to \infty } b_{n}=0$ and,
2. $\{ b_{n} \}$ is a decreasing sequence

the series $\sum a_{n}$ is convergent.

## Absolute convergence

If a series $\sum a_{n}$ converges absolutely $\left( \sum |a_{n}| \text{ converges }\right)$ then it also converges.

## Ratio test

Suppose we have the series $\sum a_{n}$. Define,
$$
L = \lim_{ n \to \infty } \left|\frac{a_{n+1}}{a_{n}}\right|
$$
Then,

1. If $L < 1$ the series is absolutely convergent (and hence convergent).
2. If $L >1$ the series is divergent.
3. If $L=1$ the series may be divergent, conditionally convergent or absolutely convergent.


## Root test

Suppose that we have the series $\sum a_{n}$. Define,

$$
L = \lim_{ n \to \infty } \sqrt[n]{|a_{n}|} = \lim_{ n \to \infty } |a_{n}|^{\frac{1}{n}}
$$
Then,

1. If $L < 1$ the series is absolutely convergent (hence convergent).
2. If $L > 1$ the series is divergent.
3. If $L = 1$ the series may be divergent, conditionally convergent, or absolutely convergent.