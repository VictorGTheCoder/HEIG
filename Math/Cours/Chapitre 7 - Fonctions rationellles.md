
**Définition :**
Pour $n(x), d(x)$ des polynômes sours forme irréductible

$$
f(x) = \frac{n(x)}{d(x)}
$$
**Opération :**
Somme, différence, quotient, ... de fonctions rationnelles donnent une fonction rationnelle.
$$
\begin{align}
f: \mathbb{R} \setminus\{1,2\}\mapsto \mathbb{R}, x \mapsto \frac{1}{(x-1)(x-2)} \\
g: \mathbb{R} \setminus\{1,3\}\mapsto \mathbb{R}, x \mapsto \frac{1}{(x-1)(x-3)}
\end{align}
$$

$$
\begin{align}
(f + g)(x) &= f(x) + g(x)  \\
&= \frac{1}{(x-1)(x-2)} + \frac{1}{(x-1)(x-3)} \\
&= \frac{(x-1)(x-3) + (x-1)(x-2)}{(x-1)^2(x-2)(x-3)} \\
&=\frac{2x-5}{(x-1)(x-2)(x-3)}
\end{align}
$$
Pour $x \in \mathbb{R} \setminus\{1,2,3\}$

#### Zéros d'une fonction rationnelle

$x_0$ telle que $f(x_0) = 0$
$f = \frac{n}{d} \quad n(x_0) = 0$
Si la fonction est bien sous forme irréductible $d(x_0) \neq 0$

**Prop :**
$f = \frac{n}{d}$, $x_0$ est un zéro de multiplicité n.
$$
\begin{align}
&(i)\text{ Si m est impair, la représantation graphique traverse l'axe des abscisses en } x_0 \\
&(ii) \text{ Si m est un nombre pair, la représentation graphique de f reste localement du même coté de l'axe} \\
\end{align}
$$
![[Pasted image 20241003090719.png]]

**Ex :**
$$
\begin{align}
f : \mathbb{R} \setminus\{-1,1\}\mapsto \mathbb{R}, x\mapsto\frac{x^2-4}{x^2-1} \\
f(x) = 0  \Leftrightarrow x^2 -4 = 0 \Leftrightarrow x = 2 \text{ ou } x = -2 \\ \\
\text{Zéros simple}
\end{align}
$$

![[Pasted image 20241003090836.png]]

#### Pôles d'une fonction rationnelle
$x_0$ telle que $d(x_0) = 0$ pour $f = \frac{n}{d}$
Forme irréductible: $n(x_0) \neq 0$
Pôle n'est jamais dans $D(f)$
Pôle de multiplicité m $\Leftrightarrow$ Racine de multiplicité m de $d(x)$

**Prop :** $f = \frac{n}{d}$, $x_0$ est un pôle de multiplicité m de f
$$
\begin{align} \\
&(i) \text{ Si m est impaire, la représentation graphique de }f\text{ part vers }+\infty \text{ d'une part et vers }-\infty \text{ d'autre part de } x_0 \\
&(ii) \text{ Si m est paire, la R.G. de f part vers } +\infty ou -\infty \text{ de part et d'autre}
\end{align}
$$

**Ex :**
$f: \mathbb{R} \setminus \{2,4\} \mapsto \mathbb{R}, x\mapsto \frac{1}{(x-2)(x-4)}$
Pôles: $x = 2, x = 4$
Pôles simple (m = 1)
![[Pasted image 20241003091856.png]]
