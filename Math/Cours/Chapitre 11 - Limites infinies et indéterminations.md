#### Limite infinie

$\lim\limits_{x \rightarrow x_0} f(x)= +\infty\text{ ou }-\infty$

$\underline{\text{Exemples}}$
$(i)\quad f(x) = \frac{1}{(x-1)^2}\text{ et } x_0 = 1$
$\quad\lim\limits_{x \rightarrow 1^-} f(x) = +\infty$
$\quad\lim\limits_{x \rightarrow 1^+} f(x) = +\infty$
La limite existe est vaut $+\infty$



$(ii) \quad g(x) = \frac{x}{x+1}$ et $x_0 = -1$

#### Limite infinie

$$
\lim\limits_{x \rightarrow x_0} f(x) = +\infty \quad \text{ou} \quad -\infty
$$

**$\underline{\text{Exemples}}$**

1. Soit $f(x) = \frac{1}{(x - 1)^2}$ et $x_0 = 1$ :
$$
\left\{
\begin{array}{l}
\lim\limits_{x \rightarrow 1^-} f(x) = +\infty
 \\
\lim\limits_{x \rightarrow 1^+} f(x) = +\infty
\end{array}
\right.
\quad \text{La limite existe est vaut } + \infty
$$

2. (Soit $g(x) = \frac{x}{x + 1}$ et $x_0 = -1$ :
$$
\left\{
\begin{array}{l}
\lim\limits_{x \rightarrow -1^-} g(x) = -\infty \\
\lim\limits_{x \rightarrow -1^+} g(x) = +\infty
\end{array}
\right.
\quad \text{La limite n'existe pas, car les deux limites latérales sont différentes.}
$$


**$\underline{\text{Propriétés}}$**
1. Sommes / différences.
	- $(+\infty) + ( +\infty) = +\infty$
	- $(-\infty) + ( -\infty) =-\infty$
	- $(+\infty) + L = +\infty$
2. Produits / Quotients
	- $(+\infty) \cdot L = \begin{cases} +\infty & \text{si } L > 0 \\ -\infty & \text{si } L < 0 \\ 0 & \text{si } L = 0 \end{cases}$

**$\underline{\text{Formes indéterminées}}$**
- $+\infty - (+\infty)$ ou $-\infty + (+\infty)$
- $0 \cdot (+\infty)$ ou $0 \cdot (-\infty)$
- $\frac{0}{0}$
- $\frac{\infty}{\infty}$
- $\infty^0$
- $0^0$
- $1^\infty$
**$\underline{\text{Exemples}}$**
1. $\lim\limits_{x \rightarrow 1} \frac{3x^2 -2x- 1}{1-x^2} = \lim\limits_{x \rightarrow 1} \frac{(x-1)(3x+1)}{(1-x)(1+x)} = \lim\limits_{x \rightarrow 1} - \frac{3x +1}{1+x} = -2$
2. $\lim\limits_{x \rightarrow \frac{1}{4}} \frac{\sqrt{x} -\frac{1}{2}}{4x-1} = \lim\limits_{x \rightarrow \frac{1}{4}} \frac{\sqrt{x} +\frac{1}{2}}{4\left( 1-\frac{1}{4} \right)}\cdot\left( \frac{\sqrt{x} + \frac{1}{2}}{\sqrt{x} + \frac{1}{2}} \right) = \lim\limits_{x \rightarrow \frac{1}{4}} \frac{1}{4\left( \sqrt{x} +\frac{1}{2} \right)} =\frac{1}{4}$
3. 
$$
\lim\limits_{x \rightarrow 2} \frac{x-2}{\sin(\pi x)}
$$
**Pour** $u = x - 2$, nous avons :

$$
= \lim\limits_{u \rightarrow 0} \frac{u}{\sin(\pi u + 2\pi)} 
$$

En utilisant la **périodicité** de la fonction sinus :

$$
= \lim\limits_{u \rightarrow 0} \frac{u}{\sin(\pi u)} 
$$
**Pour** $y = u \cdot \pi$, nous avons :
$$
\frac{1}{\pi}\lim\limits_{y \rightarrow 0} \frac{y}{sin(y)} = \frac{1}{pi}- \frac{1}{1} = \frac{1}{\pi}
$$





