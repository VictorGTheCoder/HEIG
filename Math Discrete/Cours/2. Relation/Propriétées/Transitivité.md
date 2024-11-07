---
title: Relation de transitivité
tags:
  - mathématiques
  - relation
  - transitivité
  - propriété
---

## Définition

$R$ est transitive si $\forall x,y,z \in E \quad (x,y)\in\mathbb{R} \text{ et } (y,z) \in \mathbb{R} \Rightarrow (x,z)\in \mathbb{R}$

**Conséquence**

$R^2 \subseteq R$  $R^2 = R\circ R$

## Exemples

**Exemples 1**
$$
A = \{1,2,3,4\}
\quad
R_1 = \{(2,2),(2,3),(2,4),(3,2),(3,3),(3,4)\}
$$

Cette relation est **transitive** car la définition est vérifié on peut aussi le verifier avec un calcule matriciel

$$
M(R_1) = \begin{bmatrix} 0 & 0 & 0 & 0 \\ 0 & 1 & 1 & 1 \\ 0 & 1 & 1 & 1 \\ 0 & 0 & 0& 0\end{bmatrix}
$$

On doit en suite vérifié que $R^2 \subseteq R$  Pour verifier cette inclusion on vérifie que chaque élément non nul de $M^2$ le soit également dans $M$
$$
(M(R_1))^2 = \begin{bmatrix} 0 & 0 & 0 & 0 \\ 0 & 1 & 1 & 1 \\ 0 & 1 & 1 & 1 \\ 0 & 0 & 0 & 0 \end{bmatrix}^2 = \begin{bmatrix} 0 & 0 & 0 & 0 \\ 0 & 2 & 2 & 2 \\ 0 & 2 & 2 & 2 \\ 0 & 0 & 0 & 0 \end{bmatrix} \quad \text{et} \quad M(R_1^2) = M(R_1)
$$

**Exemples 2**

$B = \{1,2,3\} \quad R_2 = \{(2,1),(2,2),(2,3),(3,2),(3,3)\}$

$$
M(R_2) = \begin{bmatrix} 0 & 0 & 0 \\ 1 & 1 & 1 \\ 0 & 1 & 1 \end{bmatrix}
$$

$$(M(R_2))^2 = \begin{bmatrix} 0 & 0 & 0 \\ 1 & 1 & 1 \\ 0 & 1 & 1 \\ \end{bmatrix}^2 = \begin{bmatrix} 0 & 0 & 0 \\ 1 & 2 & 2 \\ 1 & 2 & 2 \end{bmatrix} \quad \text{et} \quad M(R_1^2) = M(R_1)$$

La relation n'est pas transitive car  $R^2 \subseteq R$
Le problème est que $(3,2) \in R$ et $(2,1) \in R$ mais $(3,1) \notin R$


**Exemple 3** 
 $C = \{1, 2, 3\}\quad R_43 = \{\, (1,2),\ (1,3),\ (2,3) \,\}$ 
 $$ M(R_3) = \begin{bmatrix} 0 & 1 & 1 \\ 0 & 0 & 1 \\ 0 & 0 & 0 \\ \end{bmatrix} $$ Calcul de $M(R_3)^2$  : $$ M(R_4)^2 = M(R_4) \times M(R_4) = \begin{bmatrix} 0 & 0 & 1 \\ 0 & 0 & 0 \\ 0 & 0 & 0 \\ \end{bmatrix} $$  $R_4^2 \subseteq R_4$ Comparons $M(R_4)^2$ avec $M(R_4)$ : $$ M(R_4)^2 = \begin{bmatrix} 0 & 0 & 1 \\ 0 & 0 & 0 \\ 0 & 0 & 0 \\ \end{bmatrix} \quad \text{et} \quad M(R_4) = \begin{bmatrix} 0 & 1 & 1 \\ 0 & 0 & 1 \\ 0 & 0 & 0 \\ \end{bmatrix} $$
- **Observation :** Les seules paires non nulles dans $M(R_4)^2$ sont $(1,3)$, qui est également présente dans $R_4$. Les paires $(1,2)$ et $(2,3)$ sont présentes dans $R_4$ mais **ne sont pas** dans $M(R_4)^2$.

- **Conclusion :** $M(R_4)^2$ est une **sous-matrice stricte** de $M(R_4)$, tout en maintenant $R_4$ transitive.

**Exemples 4**

$E = \mathbb{Z} \quad xRy \Leftrightarrow \exists k \in \mathbb{R} \quad y-x = 5k$   transitif ?
$x,y,z \in \mathbb{R}$
$xRy$ et $yRx$
$xRy \Leftrightarrow \exists k \in \mathbb{Z} \quad y-x = 5k$
$yRz \Leftrightarrow \exists l \in \mathbb{Z} z-y = 5l$

$\underline{But} \quad z-y = 5(m)\quad \exists m\in \mathbb{Z}$
$y-x = 5k$
$z-y = 5l$

$z-x = 5(l+k) \text{ donc }  m = l+ k$
