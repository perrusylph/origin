## Exercise 2.2 (p.21)
Verify that each of the preceding examples is in fact a topology.
### Proof 
(a) We have $X$ any set whatsoever,  and let $\mathcal{T} = \mathcal{P}(X)$.
1. $X$ and $\emptyset$ are open subsets of $X$ because $X, \emptyset \in \mathcal{P}(X) = \mathcal{T}$ ($X \subset X; \emptyset \subset X)$. 
2. If $U_{1},\dots,U_{n}$ are elements of $\mathcal{T}$, it means they are all subsets of $X$, and it is clear that for any $i \in \{ 1,\dots,n \}$ $$
U_{1} \cap \cdots\cap U_{n} \subset U_{i} \subset X
	$$This means that $U_{1} \cap \cdots \cap U_{n}$ is a subset of $X$ and, as such, an element of $\mathcal{T}$.
3. If $(U_{\alpha})_{\alpha \in A}$ is any (finite or infinite) family of elements of $\mathcal{T}$, then let $x \in \bigcup_{\alpha \in A}U_{\alpha}$. It follows that there exists $\alpha \in A$ such that $x \in U_{\alpha} \subset X$. Since $x$ was arbitrary, this means that $\bigcup_{\alpha \in A} \subset X$, which implies that $\bigcup_{\alpha \in A} \in \mathcal{T}$. 

(b) Let $Y$ be any set, and let $\mathcal{T} = \{ Y,\emptyset \}$. 
1. Clearly it follows from the definition of $\mathcal{T}$ that $Y, \emptyset \in \mathcal{T}$.
2. The only posible intersections are: $Y \cap Y = Y, Y \cap \emptyset = \emptyset$ and $\emptyset \cap \emptyset = \emptyset$. These are cases seen above.
3. Only unions possible end up being either $Y$ or $\emptyset$, and these are open subsets as we know.

(c) Let $Z$ be the set $\{ 1,2,3 \}$, and declare the open subsets to be $\{ 1 \},\{ 1,2 \},\{ 1,2,3 \}$, and the empty set.
1. The empty set and $Z = \{ 1,2,3 \}$ were declared to be open subsets.
2. $\{ 1,2 \} \cap \{ 1 \} = \{ 1 \}$, $\{ 1 \} \cap \{ 1,2,3 \} = \{ 1 \}$, $\{ 1,2 \} \cap \{ 1,2,3 \} = \{ 1,2 \}$, $\{ 1 \}\cap\{ 1,2 \}\cap\{ 1,2,3 \} = \{ 1 \}$. Any intersection with the empty set gives the empty set. We have exhausted all possible intersections and found that all of them turn out to be open subsets.
3. Any union of an open set and the empty set gives itself. Any union that involves $\{ 1,2,3 \}$ gives that very set. We also have that $\{ 1 \} \cup \{ 1,2 \} = \{ 1,2 \}$. We have exhausted all the possibilities for unions and have found them to be open subsets. 
$\blacksquare$

## Exercise (2.4) (p.22)
(a) Suppose $M$ is a set and $d,d'$ are two different metrics on $M$. Prove that $d$ and $d'$ generate the same topology on $M$ if and only if the following condition is satisfied: for every $x \in M$ and every $r >0$, there exist positive numbers $r_{1}$ and $r_{2}$ such that $B_{r_{1}}^{(d')}(x) \subseteq B_{r}^{(d)}(x)$ and $B_{r_{2}}^{(d)}(x) \subseteq B_{r}^{(d')}(x)$.
### Proof
$\Rightarrow$ Let's assume that $d$ and $d'$ generate the same topology in $M$. This means that the same sets are open with respect to both metrics. We know that a set is open in a metric space if it contains an open ball around each of its points. Let $x \in M$ and let $r >0$. It is clear that $B_{r}^{(d)}(x)$ is an open set in $M$ with respect to $d$. It is, crucially, also an open set in $M$ with respect to $d'$. This means that it contains an open ball (with metric $d'$) around each of its points, in particular $x$. Let $r_{1}$ be the the radius of that ball. This means that $$
B_{r_{1}}^{(d')}(x) \subseteq B_{r}^{(d)}(x)
$$
We can similarly prove that there is $r_{2} >0$ such that $$
B_{r_{2}}^{(d)}(x) \subseteq B_{r}^{(d')}(x)
$$
$\Leftarrow$ Now let's assume the existence of $r_{1}$ and $r_{2}$ for every $r>0$ and $x \in M$ as in the exercise statement. Now, let's take w.l.o.g (we'll se why) an open set with respect to $d$. Let us call it $U$. Since $U \subset M$ is open with respect to $d$, it means that it contains an open ball (with respecto to $d$) around each of its points. This means that if we take any $x \in U$, there is $r>0$ such that $B_{r}^{(d)}(x) \subset U$. Now, using our assumption, we can find $r_{1}>0$ such that $B_{r_{1}}^{(d')}(x) \subseteq B_{r}^{(d)}(x) \subset U$. Since $x$ was arbitrary, this means that $U$ contains an open ball (with respect to $d'$) around each of its points. This proves that $U$ is also open with respect to $d'$. 
In a similar fashion, we can prove that an open set with respect to $d'$ will also be open with respect to $d$.
$\blacksquare$

(b) Let $(M,d)$ be a metric space, let $c$ be a positive real number, and define a new metric $d'$ on $M$ by $d'(x,y) = c\cdot(x,y)$. Prove that $d$ and $d'$ generate the same topology on $M$.
### Proof
Let's take $x \in M$ and $r>0$ and try to find suitable $r_{1}$ and $r_{2}$. Let $r_{1} = cr$. Then, take $y \in {B_{r_{1}}^{(d')}}(x)$. This means that $d'(x,y) < cr$, which implies that $c\cdot d(x,y) <cr$ which means that $d(x,y) <r$. Thus $B_{r_{1}}^{(d')}(x) \subseteq B_{r}^{(d)}(x)$.
Similarly, if we let $r_{2}=\frac{r}{c}$, and take $y \in B_{r_{2}}^{(d)}(x)$, we will have $d(x,y)< \frac{r}{c}$ which will imply that $d'(x,y) <r$. This means that $B_{r_{2}}^{(d)}(x) \subseteq B_{r}^{(d')}(x)$. Since we know because of (a) that this is equivalent to $d$ and $d'$ generating the same topology on $M$, we are done.
$\blacksquare$

(c) 