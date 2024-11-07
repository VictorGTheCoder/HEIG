Distributivité
$A \cap (B \cup C) = (A \cap B) \cup (A \cap C)$

**De Morgan**
$\overline{A} \cup \overline{B} = \overline{A \cup B}$
$\overline{A} \cap \overline{B} = \overline{A \cap B}$

**Absorption**
$A \cup (A \cap B) = A$
$A \cap (A \cup B) = A$

**Complémentarité**
$A \cup \overline{A} = \Omega$
$A \cap \overline{A} = \emptyset$

#### Table d'appartenance

| A   | B   | A $\cup$ B | A $\cap$ B | A $\Delta$ B |
| --- | --- | ---------- | ---------- | ------------ |
| 1   | 1   | 1          | 1          | 0            |
| 1   | 0   | 1          | 0          | 1            |
| 0   | 1   | 1          | 0          | 1            |
| 0   | 0   | 0          | 0          | 0            |

#### Cardinal d'un ensemble
$A$ un ensemble fini
$|A| = card(A)$  nombre d'élément de $A$
$|\emptyset| = 0$
$A = {{1, 2}}$ , $|A| = 2$

**Cas général**
$A$ et $B$ deux ensembles finis.
$|A \cup B| = |A| + |B| - |A \cap B|$

## 1.1 Différence symétrique

$$
\begin{align}
|A \Delta B \Delta C| &= |A| + |B| + |C| -2|A\cap B| - 2|A\cap C| - 2|B\cap C|+4 |A\cap B \cap C| \\
\end{align}
$$
Toute les parties bleu sont couverte 1 fois et sont compris dans le résultat, la partie rouge est couverte 3 fois et est aussi couverte dans le résultat.

Les parties blanches sont couverte 2fois et ne sont pas compté dans le résultat.
En somme toutes les parties couvertes un nombre impaire de fois faut partie de l'ensemble final.
![[Pasted image 20240925172355.png]]

## 1.2 Ensemble de parties
**Déf :**  $P(x)$  est définie comme l'ensemble de tous les sous-ensembles de x, c'est à dire
$P(x) = \{A | A \subseteq x\}$

**Exemples**
$x = \emptyset$    $P(\emptyset) = \emptyset$
$x = \{a,b\}$   $P(x) = \{\emptyset, \{a\}, \{b\}, \{a,b\}\}$
$x = \{a,b,c\}$ $P(x) = \{\emptyset, \{a\},\{b\},\{c\},\{a,b\}, \{a,c\}, \{b,c\},\{a,b,c\}\}$


$$
\begin{align}

&x = \emptyset &|x| = 0 \quad &|P(x)| = 1 \\
&x = \{a,b\} &|x| = 2 \quad &|P(x)| = 2^2 \\
 \\
&|x| = n &|P(x)| = e^{|x|} \\

\end{align}
$$
$\mathcal P(E) = \{\emptyset, \{a\}, \{b\}, \{c\}, \{a,b\}, \{a,c\}, \{b,c\}, E\}$

$x = \{a,b,c\}$

On sait aussi que 
$\mathcal{P}(A\cap B) = \mathcal{P}(A) \cap \mathcal{P}(B)$

$|\mathcal{P}(A)\cup \mathcal{P}(B)| = |\mathcal{P}(A)| + |\mathcal{P}(B)| - |\mathcal{P}(A\cap B)|$

#### 1.2 bis table d'équivalence
$$
X \in \mathcal P(A) \cap \mathcal P(B) \Leftrightarrow 
$$



#### 1.3 Produit cartésien
**Déf :** Le produit cartésien est définit comme tel $A \times B$ c'est l'enseble de tout dont la première composant appartient à A et la deuxième à B
Trés important de faite la distinction entre couple et ensemble
![[Cartesian_Product_qtl1.svg.png]]

**Propriétés**
$|A \times B| = |A| \cdot |B|$

$A \times \emptyset = \emptyset \times A = \emptyset$

Pas comme les ensembles l'ordre est important dans les couples $(a,b) \neq (b,a)$
$A_1 \times A_2 \times .... \times A_n = \{(a_1,a_2,...,a_n) \mid a_1 \in A_1, a_2 \in A_2, ..., a-n \in A_n\}$

Si $A$ et $B \subseteq \mathbb{R}$
![[Pasted image 20241001112543.png]]

Autres exemples
![[Pasted image 20241001112602.png]]

$A = \{0,1\} \quad B=\{a,b\}$

$\mathcal{P}(A\times B) = \{\emptyset, \{(0,a)\},\{(0,b)\},\{(1,a)\},\{(1,b)\},\{(0,a),(0,b)\},\{(0,a),(1,a)\},\{(0,a),(1,b)\}\{(1,a),(1,b)\},\{(0,a),(0,b),(1,a)\},\{(0,a),(0,b),(1,b)\}\}$