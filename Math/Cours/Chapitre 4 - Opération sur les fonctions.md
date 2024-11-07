#### 4.1 Opération de base
![[Pasted image 20240926085040.png]]
**Exemples**
$\text{Soit } f: [-2x, +\infty[ \rightarrow \mathbb{R},x\mapsto \sqrt{x + 2} \text{ et } g: \mathbb{R} \mapsto \mathbb{R}, x \rightarrow x - 1$

1) La somme $(f + g)(x) = \sqrt(x + 2) + x - 1$ Définie sur $D(f + g) = [-2x, + \infty[ \cap \mathbb{R} = [-2x, +\infty[$
2) Le quotient $f(x) / g(x)$ $D(\frac{f}{g}) = \frac{\sqrt{x+2}}{x-1}$
3) $(\frac{D(f)}{D(g)} = ([.2, +\infty[ \cap \mathbb{R}) \setminus\{x\in\mathbb{R}|x-1=0\} = [-2,+\infty[ \setminus\{1\}$

#### 4.3 Composition de fonctions
**Composé**
$(g \circ f)(x) = g(f(x))$
**Ex**
$f: \mathbb{R}\rightarrow\mathbb{R}m x \mapsto x^2$
$g: \mathbb{R+} \rightarrow\mathbb{R}| x \mapsto \sqrt{x}$

$(g \circ f)(x) = g(f(x)) = \sqrt{x^2} = |x|$
$D(g \circ f) = \{x \in \mathbb{R} | x\in \mathbb{R} \text{ et } x^2 \in \mathbb{R+}\} = \mathbb{R}$

$(f \circ g)(x) = f(g(x)) = (\sqrt{x})^2 = x$
$D(f \circ g) = \{x \in \mathbb{R} | x\in \mathbb{R}$

#### 4.4 Inversion d'une fonction
$f: E \rightarrow F$
$f^{-1} : F\rightarrow E$

$f \text{ doit être bijective ca veut dire qu'elle est à la fois surjéctive et injéctive}$
$\text{Sujective } Im(f) = F$
$\text{injective}: \forall (x1,x2) \in E \quad [f(x1) = f(x2)] \Rightarrow [x1 = x2]$
ou
$\forall (x1,x2) \in E \quad [f(x1) \neq f(x2)] \Rightarrow [x1 \neq  x2]$

**Ex**
$f: \mathbb{R} \rightarrow\mathbb{R}, x \mapsto x^3$
$f \text{ est surjéctive: } Im(f) = \mathbb{R}$
$f \text{est injéctive }$
Donc $f$ est bijéctive
![[Pasted image 20240926092219.png]]

$f^{-1}(y) = x \Leftrightarrow y = f(x)$
**Ex**
$f: \mathbb{R}\mapsto\mathbb{R}, x\mapsto x^3$
$y = f(x) = x^3 \Leftrightarrow x = y^{\frac{1}{3}} = f^{-1}(y)$

$f^{-1}: \mathbb{R}\mapsto \mathbb{R}$
$x \mapsto x^{\frac{1}{3}}$

![[Pasted image 20240926093353.png]]

**Remarque**
La fonction identité

Lorsque j'applique X je retrouve X
$f^{-1} \circ f = idE$ Identité sur l'ensemble E
$f \circ f^{-1} = idF$ Identité sur l'enseble F