---
title: Composition de relation
author: Victor Giordani
created: 2024-04-27
updated: 2024-04-27
tags:
  - discrètes
  - propriété
  - relation
  - mathématiques
---
## Définition

Soit $R$ une [relation](Relations) de  $A$ vers  $B$ et $S$ une relation de $B$ vers $C$. La composition de $R$ par $S$, notée  $S \circ R$, est la relation de $A$ vers $C$ formée des couples $(a, c) \in A \times C$ pour lesquels il existe (au moins) un élément $b \in B$ avec $(a, b) \in R$ et  $(b, c) \in S$ :

$$ S \circ R = \{(a, c) \in A \times C \mid \exists b \in B \text{ avec } (a, b) \in R \text{ et } (b, c) \in S \}. $$

## Exemples

**EXEMPLE 1.**  
Soit $A$ l’ensemble des étudiants et étudiantes de l’école, $B$ l’ensemble des cours dispensés ce semestre et $C$ l’ensemble des enseignants et enseignantes de l’école. Soit encore les relations :

- $R = \{(a, b) \in A \times B \mid \text{l'étudiant-e } a \text{ suit le cours } b\}$
- $S = \{(b, c) \in B \times C \mid \text{le cours } b \text{ est donné par l'enseignant-e } c\}$

La composition $S \circ R$ est l’ensemble des couples $(a, c)$ où l’étudiant-e $a$ suit au moins un cours donné par l’enseignant-e $c$ ce semestre.

**EXEMPLE 2.**  
Soient les ensembles $A = \{1, 2, 3, 4\}$, $B = \{a, b, c, d\}$ et $C = \{x, y, z\}$ et les relations :

- $R = \{(1, a), (2, d), (3, a), (3, b), (3, d)\}$
- $S = \{(b, x), (b, z), (c, y), (d, z)\}$

On peut calculer la relation $S \circ R$ à partir des graphes de $R$ et $S$ :
![[Pasted image 20241015113154.png]]

En utilisant les graphes, la composition $S \circ R$ est :
$$ S \circ R = \{(2, z), (3, x), (3, z)\} $$.
$$
\begin{gather} 
\text{Define the matrices for relations R and S:} \\\\
M(R) = \begin{bmatrix} 1 & 0 & 0 & 0 \\ 0 & 0 & 0 & 1 \\ 1 & 1 & 0 & 1 \\ 0 & 0 & 0 & 0 \end{bmatrix}, \quad M(S) = \begin{bmatrix} 0 & 0 & 0 \\ 1 & 0 & 1 \\ 0 & 1 & 0 \\ 0 & 0 & 1 \end{bmatrix} \\\\
M(S\circ R) \text{is given by: } M(S) \cdot M(R) \\ \\
M(R) \cdot M(S) = 
\begin{bmatrix} 1 & 0 & 0 & 0 \\ 0 & 0 & 0 & 1 \\ 1 & 1 & 0 & 1 \\ 0 & 0 & 0 & 0 \end{bmatrix} 
\cdot \begin{bmatrix} 0 & 0 & 0 \\ 1 & 0 & 1 \\ 0 & 1 & 0 \\ 0 & 0 & 1 \end{bmatrix} 
= \begin{bmatrix} 0 & 0 & 0 \\ 0 & 0 & 1 \\ 1 & 0 & 2 \\ 0 & 0 & 0 \end{bmatrix} \end{gather}
$$

Ensuite pour obtenir la matrice de la relation composé, il suffit de remplacer dans le produit de $M(R)\cdot M(S)$ tout les éléments supérieurs à $1$ par $1$.
On obtient

$$
M(S\circ R) = M(R) \cdot M(S) = 
\begin{bmatrix} 0 & 0 & 0 \\ 0 & 0 & 1 \\ 1 & 0 & 1 \\ 0 & 0 & 0 \end{bmatrix} 
$$
On peut ensuite généraliser pour plusieurs relations.
![[Pasted image 20241015115724.png]]

