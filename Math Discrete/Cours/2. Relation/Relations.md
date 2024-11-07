
Une relation d'un ensemble $A$ vers $B$

$R \subseteq A \times R$

![[Pasted image 20241015111857.png]]

$\underline{Exemple}$
A: Ensemble des étudiants
B: Ensemble des cours dispensé

$R$


$A = \{a_1,a_2\}$
$B = \{b_1,b_2,b_3\}$
$R=\{(a_1,b_1),(a_1,b_2),(a_2,b_2),(a_2,b_3)\} \subseteq A\times B$

$$
M(R) =
\begin{pmatrix}
1\quad 1\quad 0 \\
0 \quad 1\quad 1
\end{pmatrix}
$$
La relation complémentaire d’une relation $R$ de $A$ vers $B$ est la relation $\overline{R}$, elle aussi de $A$ vers $B$, formée de tous les couples du produit cartésien $A \times B$ n’appartenant pas à $R$ :

$$ \overline{R} = \{(a, b) \in A \times B \mid (a, b) \notin R \} = (A \times B) \setminus R. $$

La relation inverse d’une relation $R$ de $A$ vers $B$ est la relation $R^{-1}$, de $B$ vers $A$, obtenue en inversant l’ordre des composantes de chacun des couples de $R$ :

$$ R^{-1} = \{(b, a) \in B \times A \mid (a, b) \in R \}. $$

**EXEMPLE.** Sur l’ensemble des personnes, la relation complémentaire de la relation « est le fils ou la fille de » est la relation « n’est pas l’enfant de » alors que la relation inverse est la relation « est le père ou la mère de ».


une relation sur un ensemble (4 Propriété)

- [[Symétrie]]
- [[Antisymétrie]]
- [[Réflexivité]]
- [[Transitivité]]
