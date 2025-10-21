2025-07-19 17:09

Tags: [[math]], [[3- Tags/calculus]]
## Limit of a sequence

Let $\{ a_{n} \}$ be a sequence in $\mathbb{R}$. Let $L \in \mathbb{R}$, we say $L$ is the limit of the sequence $\{  a_{n}\}$ if for every $\varepsilon >0$ there is a natural number $n_{0}$ such that for every $n \geq n_{0}$ it holds that $|a_{n}-L| < \varepsilon$. 

If a sequence has $L$ as a limit we say it converges to a $L$ and denote it like this:
$$
L = \lim_{ n \to \infty } a_{n}
$$
## Properties of sequences
![[Pasted image 20250719170959.png]]
## Squeeze theorem (Sandwich)
![[Pasted image 20250719171222.png]]
## Absolute value

If $\lim_{ n \to \infty }|a_{n}| = 0$ then $\lim_{ n \to \infty } a_{n} = 0$

## Regarding $r^n$

The sequence $\{ r^{n} \}_{n=0}^{\infty}$ converges if $-1<r \leq 1$ and diverges for all other values of $r$. Also,
$$
\lim_{ n \to \infty } r^{n} = \begin{cases}
0 & \text{if -1<r<1} \\
1 & \text{if r = 1}
\end{cases}
$$
If $r>1, \lim_{ n \to \infty } r^{n} = \infty$.
## Odd and even subsequence convergence give original sequence convergence
![[Pasted image 20250719173700.png]]
## Convergence of bounded and monotonic sequences

- If $\{ a_{n} \}$ converges it is bounded.
- If $\{ a_{n} \}$ is bounded ($\exists M : \forall n \in \mathbb{N} |a_{n}| \leq M$) and monotonic (increasing or decreasing) then $\{ a_{n} \}$ is convergent.

## Divergent sequence

We say that a sequence $\{ a_{n} \}$ diverges to infinity if $\forall M \in \mathbb{R}$ there is a $n_{0} \in \mathbb{N}$ such that if $n \geq n_{0}$ then $M < a_{n}$. If this happens we will denote it this way:
$$
\lim_{ n \to \infty }  a_{n} = \infty 
$$
- If there is $n_{1} \in \mathbb{N}$ such that $a_{n} \leq b_{n}$ for all $n \geq n_{1}$ and $\{ a_{n} \}$ is divergent, then $\{ b_{n} \}$ is divergent as well.
- Sum, product and scalar multiplication of divergent is divergent.
- Unbounded and increasing sequence is divergent.
## Bolzano-Weierstrass Theorem
- (Lemma) Every sequence has a monotonic subsequence.
- This implies that every bounded sequence has a bounded subsequence.
- This subsequence is also bounded, which makes it convergent.

## Subsequences

If all subsequences of a bounded sequence $\{ a_{n} \}$ converge to $L$, then $\{ a_{n} \}$ also converges to $L$.

## Cauchy sequence
We say that a sequence $\{ a_{n} \}$ of real numbers is a Cauchy sequence if for every $\varepsilon >0$ there is a natural number $k$ such that for every natural numbers $n,m$ such that $n,m \geq k$ it holds that $|a_{n}-a_{m}| < \varepsilon$.

- Sum of Cauchy sequences is Cauchy.
- Every Cauchy sequence is bounded.
- Every Cauchy sequence in $\mathbb{R}$ converges. (This makes the real numbers a complete space).
# References
