2025-09-25 12:52

Tags: [[math]], [[linear algebra]]

## Sum of eigenspaces is a direct sum

Suppose $T \in \mathcal{L}(V)$ and $\lambda_{1},\dots,\lambda_{m}$ are distinct eigenvalues of $T$. Then
$$
E(\lambda_{1},T) + \cdots + E(\lambda_{m},T)
$$
is a direct sum. Furthermore, if $V$ is finite-dimensional, then 
$$
\text{dim } E(\lambda_{1},T)+\cdots+\text{dim }E(\lambda_{m},T) \leq \text{dim }V.
$$
## Conditions equivalent to diagonalizability

Suppose $V$ is finite-dimensional and $T \in \mathcal{L}(V)$. Let $\lambda_{1},\dots,\lambda_{m}$ denote the distinct eigenvalues of $T$. Then the following are equivalent.

(a) $T$ is diagonalizable.
(b) $V$ has a basis consisting of eigenvectors of $T$.
(c) $V = E(\lambda_{1},T) \oplus \cdots \oplus E(\lambda_{m},T)$.
(d) $\text{dim }V = \text{dim }E(\lambda_{1},T) + \cdots + \text{dim }E(\lambda_{m},T)$.

## Enough eigenvalues implies diagonalizability

Suppose $V$ is finite-dimensional and $T \in \mathcal{L}(V)$ has $\text{dim }V$ distinct eigenvalues. Then $T$ is diagonalizable.

## Necessary and sufficient conditions for diagonalizability

Suppose $V$ is finite-dimensional and $T \in \mathcal{L}(V)$. Then $T$ is diagonalizable if and only if the minimal polynomial of $T$ equals $(z-\lambda_{1})\cdots(z-\lambda_{m})$ for some list of numbers $\lambda_{1},\dots,\lambda_{m} \in F$.




# References
