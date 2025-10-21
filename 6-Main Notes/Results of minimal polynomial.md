2025-09-23 20:03

Tags: [[math]], [[linear algebra]]

## Existence of eigenvalues

Every operator on a finite-dimensional nonzero complex vector space has an eigenvalue.

## Existence, uniqueness, and degree of minimal polynomial

Suppose $V$ is finite-dimensional and $T \in \mathcal{L}(V)$. Then there is a __unique__ monic polynomial $p \in \mathcal{P}(F)$ of smallest degree such that $p(T) = 0$. Furthermore, $\text{deg } p \leq \text{dim } V$. 

This is the minimal polynomial. 

## Eigenvalues are the zeros of the minimal polynomial

Suppose $V$ is finite-dimensional and $T \in \mathcal{L}(V)$.

(a) The zeros of the minimal polynomial of $T$ are the eigenvalues of $T$.

(b) If $V$ is a complex vector space, then the minimal polynomial of $T$ has the form 
$$
(z-\lambda_{1})\cdots(z-\lambda_{m}),
$$
where $\lambda_{1}, \dots, \lambda_{m}$ is a list of all eigenvalues of $T$, possibly with repetitions.

## $q(T) = 0 \iff q$ is a polynomial multiple of the minimal polynomial

Suppose $V$ is finite-dimensional, $T \in \mathcal{L}(V)$, and $q \in \mathcal{P}(F)$. Then $q(T) = 0$ if and only if $q$ is a polynomial multiple of the minimal polynomial of $T$. 

## Minimal polynomial of a restriction operator

Suppose $V$ is finite-dimensional, $T \in \mathcal{L}(V)$, and $U$ is a subspace of $V$ that is invariant under $T$. Then the minimal polynomial of $T$ is a polynomial multiple of the minimal polynomial of $T|_{U}$.

## $T$ not invertible $\iff$ constant term of minimal polynomial of $T$ is $0$

Suppose $V$ is finite-dimensional and $T \in \mathcal{L}(V)$. Then $T$ is not invertible if
and only if the constant term of the minimal polynomial of $T$ is $0$.

# References
