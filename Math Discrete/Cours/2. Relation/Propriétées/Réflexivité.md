---
title: Relation de réfléxivité
tags:
  - mathématiques
  - relation
  - propriété
  - discrètes
---
## Définition

Une [relation](Relations) $R$ sur un ensemble $A$ est réflexive si et seulement si $(a, a) \in R$ pour tout élément $a \in A$.
$$
(a,b) \in R \Rightarrow (b,a) \in R
$$

**Dit autrement,** une relation sur l’ensemble $A$ est réflexive si et seulement si chaque élément de $A$ est en relation avec lui-même.

 Si l’ensemble $A$ est fini, une relation $R$ sur $A$ est réflexive si et seulement si la diagonale principale de la matrice $M(R)$ de la relation ne contient que des 1.
 
**Matrice de relation réflexive**
$$
\begin{bmatrix}
1 & . & . & . \\
. & 1 & . & . \\
. & . & 1 & . \\
. & . & . & 1 \\
\end{bmatrix}
$$
## Exemples

**EXEMPLE 1.** La relation d’inclusion (sur une collection d’ensembles) est réflexive car $S \subseteq S$ pour tout ensemble $S$.

**EXEMPLE 2.** La relation « est le fils/la fille de » (sur l’ensemble des personnes) n’est pas réflexive car personne n’est le fils/la fille de lui/elle-même. (Une telle relation est dite irréflexive.)

**EXEMPLE 3.** La relation $R = \{(x, y) \in \mathbb{N}^2 \mid x < 2y\}$ n’est pas réflexive car $(0, 0) \notin R$ (même si $(x, x) \in R$ pour tout $x > 0$).