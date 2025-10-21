2025-08-13 09:40

Tags: [[math]], [[linear algebra]]

# Orthogonal projection
Check main properties and results in Axler (Section 6C).

## Matrix form of orthogonal projection
Let's say $$A = \begin{bmatrix}
w_{1} & w_{2} & \dots & w_{m}
\end{bmatrix}$$
Where $w_{1}, \dots w_{m}, m \leq \text{dim}(V)$ is a basis for a subspace $W \subset V$. Then if $x \in V$,
$$
\text{proj}_{W}(x) = A(A^{T}A)^{-1}A^{T}x
$$

_Note:_ A useful formula that arises as a step in the proof is this:
$$
A^{T}x = A^{T}Av
$$
where $Av = \text{proj}_{W}(x)$.
## Projection onto a vector

If $u,v \in V$, then we have 
$$
\text{proj}_{v}(u) = \frac{\langle u,v \rangle}{\lvert \lvert v \rvert  \rvert ^{2}}
v = \frac{VV^{T}}{\lvert \lvert v \rvert  \rvert ^{2} }u$$
where $$V = \begin{pmatrix}
v_{1} \\
v_{2} \\
\vdots \\
v_{n}
\end{pmatrix}$$ and $v = (v_{1},v_{2},\cdots, v_{n})$.


# References

Linear Algebra Done Right by Sheldon Axler
[Standard Matrix of Projection Formula Derivation by STEM Support](http://bit.ly/46QxABG)
