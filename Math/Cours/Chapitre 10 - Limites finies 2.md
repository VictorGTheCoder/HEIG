#### $\underline{\text{10.1 Limites finies à l'infini}}$
$\lim\limits_{x \rightarrow \infty} f(x) = L_1, L_1\in \mathbb{R}$
$\lim\limits_{x \rightarrow -\infty} f(x) = L_2, L_2\in \mathbb{R}$

$\underline{Ex:}$
$\lim\limits_{x \rightarrow +\infty} \frac{4x^2 -3x + 1}{1-3x^2} = \lim\limits_{x \rightarrow \infty} \frac{x^2\left( 4-\frac{3}{x} + \frac{1}{x^2} \right)}{x^2\left( -3 + \frac{1}{x^2} \right)} =-\frac{4}{3}$

#### $\underline{\text{10.2 Propriétés des limites finies}}$
$x_0\in \mathbb{R} \cup \{+\infty,-\infty\}$
$$
\begin{gather}
f,g, \lim\limits_{x \rightarrow x_0} f(x) = L_1$ et  $\lim\limits_{x \rightarrow x_0} = L_2
\end{gather}
$$

![[Pasted image 20241010093631.png]]

$\underline{Encadrement}$
$x_0\in \mathbb{R} \cup \{+\infty,-\infty\}$
$f(x) \leq h(x) \leq g(x)$ $\forall x$ au voisiniage de $x_0$
Si $\lim\limits_{x \rightarrow 0}f(x) = \lim\limits_{x \rightarrow 0}g(x) =L$, alors $\lim\limits_{x \rightarrow 0}h(x) = L$


$\underline{\text{Ex:}}$
On trouver $\lim\limits_{x \rightarrow 0} \frac{sin(x)}{x}$
On sait que $\frac{sin(x)}{2} \leq \frac{x}{2} \leq \frac{tan(x)}{2} \quad \forall{x}\in]0,\frac{\pi}{2}[$
$\Rightarrow \frac{sin(x)}{x}\leq 1$ et $x\leq \frac{sin(x)}{cos(x)} \Leftrightarrow cos(x) \leq  \frac{sin(x)}{x}$

$f(x) = cos(x) \quad h(x) = \frac{sin(x)}{x} \quad g(x) = 1$

$\lim\limits_{x \rightarrow 0^+} cos(x) = 1$
$\lim\limits_{x \rightarrow 0^+} 1 = 1$

$\Rightarrow \lim\limits_{x \rightarrow 0^+} \frac{sin(x)}{x} = 1$

$\underline{\text{Ex2:}}$
$\lim\limits_{x \rightarrow 0} \frac{3tan(x)}{2x} = \lim\limits_{x \rightarrow 0} \frac{3}{2}\cdot \frac{sin(x)}{x}\cdot \frac{1}{cos(x)} = \frac{3}{2 }\cdot 1 \cdot \frac{1}{1} = \frac{3}{2}$

![[Pasted image 20241010095012.png]]

![[Pasted image 20241010094958.png]]


