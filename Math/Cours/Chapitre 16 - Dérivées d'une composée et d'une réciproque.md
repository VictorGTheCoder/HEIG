
## Composé
On a 2 fonctions $f$ et $g$

On veut obtenir la dérivée de leur composé 
$$
(g \circ f)'(x) = g'(f(x)) \cdot f'(x)
$$
On peut généraliser pour des composé à autant d'éléments que l'on veut

$$
\begin{align}
(h\circ g \circ f)'(x) &= h'((g\circ f)(x)) \cdot (g\circ f)'(x)\\
&=h'(g(f(x))) \cdot g'(f(x)) \cdot f'(x)

\end{align}
$$

### Exemples

**Exemple 1**
$h(x) = \sqrt{x^2 + 1}$

$g(x) = \sqrt{x} \to g'(x) = \frac{1}{2}x^{-\frac{1}{2}} = \frac{1}{2\sqrt{x}}$
$f(x) = x^2 + 1 \to f'(x) = 2x$
$h(x) = (g\circ f) (x)$
$h'(x) = \frac{1}{2\sqrt{x^2 +1}}$

**Exemple 2**
$h(x) = [f(x)]^{\alpha} = (g\circ f)(x)$ avec $g(x) = x^\alpha \to g'(x) = \alpha \cdot x^{\alpha -1}$
$h'(x) = \alpha (f(x))^{\alpha - 1} \cdot f'(x)$

**Exemple 3**
$exp_a(x) = a^x$
On veut trouver $exp_a'(x) = ?$

$exp_a(x) = a^x = exp(ln(a^x)) = exp(x\cdot ln(a))$
On peut poser
$h(x) = (g\circ f)(x) = exp(x\cdot ln(a))$
$f(x) = x\cdot ln(a)$ et $g(x) = exp(x)$

$exp_a'(x) = g'(f(x)) \cdot f'(x) = exp'(x\cdot ln(a)) \cdot ln(a) =exp_a(x) \cdot ln(a)$

## Réciproque
$$
(f^{-1})'(x) = \frac{1}{f'(f^{-1}(x))}
$$


### Exemples

**Exemple 1**
$$
arctan'(x) = \frac{1}{tan'(arctan(x))} = \frac{1}{1 + tan^2(arctan(x))} =\frac{1}{1+x^2}
$$

**Exemple 2**
$a \in R^{*}_+ \setminus \{1\}$
$(log_a)'(x) = \frac{1}{(exp_a)'(log_a(x))} = \frac{1}{exp_a(log_a(x))\cdot ln(a)} = \frac{1}{x\cdot ln(a)}$

On en déduit que $log_e'(x) = ln'(x) = \frac{1}{x}$


