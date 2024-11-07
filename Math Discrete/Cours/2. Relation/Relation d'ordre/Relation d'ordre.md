Une **relation d'ordre** sur un ensemble est une relation binaire qui est simultanément :

- **[Réflexive](Réflexivité.md)** 
- **[Antisymétrique](Antisymétrie.md)** 
- **[Transitive](Transitivité.md)** 

## Types de relations d'ordre

### Ordre partiel

Si il existe au moins deux éléments de l'ensemble étant non [[Comparabilité d'éléments|comparable]]

### Ordre total

Un **ordre total** (ou **ordre linéaire**) si toute paire d'élément $A$ est [[Comparabilité d'éléments|comparable]].
Autrement dit pour tout éléments distincts $a$ et $b$ de $A$, soit $a$ $R$ $b$, soit $b$ $R$ $a$.
$\forall a,b \in A\mid a \neq b \Rightarrow (a$ $R$ $b$ ou $b$ $R$ $a)$
#### Propriété
**Matrice de relation**
Si $R$ est une relation d’ordre sur
un ensemble $A$ fini, $R$ est un ordre total si
et seulement si la matrice $M(R)$ ne contient
pas deux $0$ en symétrie par rapport à sa diagonale principale car cette disposition correspondrait à deux éléments non comparables.

**Ordre pas total**
$$
\begin{bmatrix}
. & . & . & . \\
. & . & 0 & . \\
. & 0 & . & . \\
. & . & . & . \\
\end{bmatrix}
$$

**Diagramme de Hasse**
Dans un ordre total, le diagramme est une chaîne linéaire sans branches.
## Exemples

- **Inclusion des ensembles** : Sur l'ensemble des parties d'un ensemble donné, la relation $\subseteq$ est un ordre partiel.
- **Divisibilité** : Sur les entiers naturels $\mathbb{N}$, la relation $a \mid b$ ($a$ divise $b$) est un ordre partiel.
- **Ordre usuel sur les nombres réels** : La relation $\leq$ est un ordre total sur $\mathbb{R}$.

## Représentation graphique

### Diagrammes de Hasse

Les diagrammes de Hasse sont utilisés pour représenter graphiquement les ordres. Chaque élément est représenté par un point, et une arête relie deux éléments si l'un est immédiatement supérieur à l'autre.

# Diagramme de Hasse de la relation d'inclusion

Pour la relation d’inclusion sur $\mathcal{P}(\{1,2\}) = \{\emptyset, \{1\}, \{2\}, \{1,2\}\}$, on a la suite de graphe.
   
![[Diagrame de Hasse.png]]

## Propriétés supplémentaires

- **Élément minimal et maximal** :
  - Un élément $a$ est **minimal** s'il n'existe aucun $b$ tel que $b < a$.
  - Un élément $a$ est **maximal** s'il n'existe aucun $b$ tel que $a < b$.
- **Plus petit et plus grand élément** :
  - Un **plus petit élément** est un élément qui est inférieur ou égal à tous les autres éléments.
  - Un **plus grand élément** est un élément qui est supérieur ou égal à tous les autres éléments.
- **Chaînes et antichaînes** :
  - Une **chaîne** est un sous-ensemble totalement ordonné.
  - Une **antichaîne** est un ensemble d'éléments mutuellement incomparables.

## Treillis

Un **treillis** est un ordre partiel dans lequel tout couple d'éléments possède une borne supérieure (supremum) et une borne inférieure (infimum).

## Bon ordre

Un ensemble est **bien ordonné** si toute partie non vide possède un plus petit élément. Cela implique que l'ordre est total et qu'il n'y a pas de suites infiniment décroissantes.

## Lemme de Zorn

Le **lemme de Zorn** stipule que si chaque chaîne ascendante dans un ensemble partiellement ordonné admet une borne supérieure, alors l'ensemble contient au moins un élément maximal. Ce lemme est équivalent à l'axiome du choix et a de nombreuses applications en mathématiques.

