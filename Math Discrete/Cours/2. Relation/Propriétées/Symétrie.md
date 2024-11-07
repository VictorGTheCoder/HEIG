---
title: Relation symétrique
tags:
  - mathématiques
  - discrètes
  - relation
  - symétrique
  - propriété
---
## Définition

$R$ est une [relation](Relations) est symétrique si :  
$$
\forall x,y \in E\quad (x,y)\in{R} \Rightarrow (y,x)\in{R}
$$
Autrement dit si $R^{-1} = R$

Si l’ensemble $A$ est fini, une relation $R$ sur $A$ est symétrique si et seulement si la matrice $M (R)$ de la relation est symétrique par rapport à sa diagonale
**Matrice de relation symétrique**
$$
\begin{bmatrix}
1 & 2 & 0 & 5 \\
2 & 2 & 1 & 2 \\
0 & 1 & 3 & 0 \\
5 & 2 & 0 & 4 \\
\end{bmatrix}
$$
## Exemples

**EXEMPLE 1.** La relation, sur l’ensemble des pays, formée de tous les couples de pays limitrophes est symétrique.

**EXEMPLE 2.** La relation sur $\mathbb{Z}$ où $x$ est en relation avec $y$ si et seulement si $x$ a la même parité que $y$ (c’est-à-dire si et seulement si $x$ et $y$ ont la même parité) est symétrique.

**EXEMPLE 3.** La relation « est le fils/la fille de » (sur l’ensemble des personnes) n’est pas symétrique.


**EXEMPLE** 4.
$E=\mathbb{Z}$
$$
\begin{align}
xRy\Leftrightarrow 5 \mid y -x &\Leftrightarrow \exists k \in \mathbb{Z} \quad y-x = 5k \\
&\Leftrightarrow \exists k \in \mathbb{Z} \quad x-y = 5(-k) \\
&\Leftrightarrow \exists k' \in \mathbb{Z} \quad x-y = 5k' \\
&\Leftrightarrow (y,x) \in \mathbb{R}
\end{align}
$$
$\text{R est symétrique}$